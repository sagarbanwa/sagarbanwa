# Grav CMS 1.6.30 + Admin Plugin 1.9.18 — Persistent XSS (`Page Title`)

| | |
|---|---|
| **CVE** | none assigned |
| **Product** | Grav CMS 1.6.30, Admin plugin 1.9.18 |
| **Vulnerability** | Stored / persistent Cross-Site Scripting (CWE-79) |
| **Privilege required** | Authenticated admin-panel user able to create/edit pages |
| **Discovered / reported by** | Sagar Banwa |
| **Public** | Exploit-DB [49264](https://www.exploit-db.com/exploits/49264), Dec 2020 |

## Summary

The Grav admin panel stores the **Page Title** field without output encoding. A script
payload entered when creating a new page is persisted and executed in the admin interface
whenever that page is listed or opened.

## Steps to reproduce

1. Log in to `/admin`.
2. **Pages → Add** a new page.
3. Set the **Page Title** to:
   ```
   <script>alert(document.domain)</script>
   ```
4. Save. Re-open the Pages view / the page editor — the payload executes in the admin session.

## Impact

Persistent script execution in the authenticated admin context: session hijacking, CSRF-token
theft, or admin actions performed as the victim. Relevant in multi-author installations where
lower-trust editors can seed titles rendered to an administrator.

## Remediation

Update Grav and the Admin plugin. Root cause: apply context-aware HTML encoding to the page
title at every admin-side output sink.
