# mojoPortal Forums 2.7.0.0 — Persistent XSS (forum `Title`)

| | |
|---|---|
| **CVE** | none assigned |
| **Product** | mojoPortal 2.7.0.0 — Forums feature |
| **Vulnerability** | Stored / persistent Cross-Site Scripting (CWE-79) |
| **Privilege required** | Authenticated user able to create/edit a forum (`EditForum.aspx`) |
| **Discovered / reported by** | Sagar Banwa |
| **Public** | Exploit-DB [49184](https://www.exploit-db.com/exploits/49184), Dec 2020 |

## Summary

The forum **Title** field on `EditForum.aspx` is stored and later rendered without
output encoding. A payload set as a forum title executes whenever the forum details are
displayed to an administrator or a visitor.

## Steps to reproduce

1. Authenticate and open **Forums → add/edit a forum** (`EditForum.aspx`).
2. Set the forum **Title** to:
   ```
   <script>alert(1)</script>
   ```
3. Save and view the forum list / forum details page. The stored script runs in the
   viewer's session.

## Impact

Stored XSS reachable by forum visitors and administrators — cookie/session theft, forged
authenticated actions, or content manipulation.

## Remediation

Upgrade mojoPortal. Root cause: server-side validation plus context-aware HTML encoding of
the forum title at all output sinks.
