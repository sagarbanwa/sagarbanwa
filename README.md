# Hi, I'm Sagar Banwa 👋

**Offensive Security Engineer · Red Teamer · Bug Bounty Hunter**
IBM Cloud Platform Red Team · OSCP · Bengaluru, India

I break web apps, APIs, cloud platforms, and — increasingly — AI/LLM systems, then help
teams fix them. I've published CVEs, written the tooling I hunt with, and been credited
in the security acknowledgments of Apple, Google, the United Nations, Nokia, Dell, and more.

- 🔭 **Now:** Red Team @ IBM Cloud Platform — offensive assessments of cloud infrastructure and services
- 🛡️ **Focus:** web/API pentesting, authorization & business-logic flaws, cloud attack surface, AI/LLM security
- 🧰 **I build:** recon and bug-bounty automation (see pinned repos)
- 🎯 **Bug bounty:** HackerOne · Bugcrowd · Yogosha · YesWeHack · Intigriti
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/sagarbanwa/)

---

## 🐞 Published CVEs & Advisories

| CVE | Product | Class | Reference | Date |
|---|---|---|---|---|
| **CVE-2020-29240** | LEPTON CMS 4.7.0 | Stored XSS (`URL` field, Pages) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2020-29240) · [Exploit-DB 49137](https://www.exploit-db.com/exploits/49137) | Nov 2020 |
| **CVE-2023-46391** | WEBIGniter v28.7.23 | Stored XSS (Categories) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2023-46391) · [Exploit-DB 51807](https://www.exploit-db.com/exploits/51807) | Oct 2023 |
| *(no CVE assigned)* | Grav CMS 1.6.30 + Admin Plugin 1.9.18 | Persistent XSS (`Page Title`) | [Exploit-DB 49264](https://www.exploit-db.com/exploits/49264) | Dec 2020 |
| *(no CVE assigned)* | mojoPortal Forums 2.7.0.0 | Persistent XSS (forum `Title`) | [Exploit-DB 49184](https://www.exploit-db.com/exploits/49184) | Dec 2020 |

📚 **Google Hacking Database (GHDB):** multiple Google dorks published to Exploit-DB for
sensitive-file and exposed-config discovery (e.g. `pom.xml`, `auth.json`, `nginx.conf`,
`/includes/OAuth2` directory-listing dorks) — [GHDB 8169](https://www.exploit-db.com/ghdb/8169),
[5762](https://www.exploit-db.com/ghdb/5762), [5759](https://www.exploit-db.com/ghdb/5759).

> Reported **50+ vulnerabilities** to India's **NCIIPC** (National Critical Information
> Infrastructure Protection Centre) responsible-disclosure program.

---

## 🏆 Hall of Fame & Security Acknowledgments

Credited for responsibly disclosed vulnerabilities by:

**Apple** (2021) · **Google** · **United Nations** · **Nokia** · **Dell** · **Tidepool**
· **EC-Council** · **NCIIPC (India)**

<sub>Add direct acknowledgment-page links / screenshots under each as you confirm them.</sub>

---

## 🤖 AI / LLM Security

- Building **Bastion** — a defense-in-depth web/API security-assessment agent that hunts
  every vuln class to depth and escalates instead of assuming a surface is safe.
- Deep interest in **LLM red-teaming**: prompt injection, tool/agent abuse, insecure
  output handling, vector-store BOLA, leaked-key scope abuse, and SSRF via model tooling.
- Why this matters to me: as agents get real capabilities, offensive-security rigor is
  what keeps them safe to deploy — the same escalate-every-datum discipline I use on web apps.

---

## 🧰 Open-Source Tooling

| Repo | What it does |
|---|---|
| [`checklist-BB`](https://github.com/sagarbanwa/checklist-BB) | Bug bounty methodology checklist |
| [`BountySleuth`](https://github.com/sagarbanwa/BountySleuth) | Bug bounty companion — WAF detection, CSRF/XSS/DOM analysis, CORS, cloud detection, smart payloads |
| [`Subsonly`](https://github.com/sagarbanwa/Subsonly) | Subdomain enum (subfinder + amass + assetfinder) filtered to live hosts with httpx |
| [`CIDR`](https://github.com/sagarbanwa/CIDR) | Expand an org's CIDR ranges into scannable IP lists for httpx |
| [`maxlim`](https://github.com/sagarbanwa/maxlim) | Subdomain discovery wrapper around ProjectDiscovery tooling |

---

## 🛠️ Toolbox

**Offensive:** Burp Suite Pro · nuclei · ffuf · sqlmap · ProjectDiscovery suite
(subfinder/httpx/dnsx/naabu/katana/tlsx) · Frida · Objection · nmap · Metasploit
**Cloud:** AWS · IBM Cloud · Azure · container / K8s security
**Certs:** OSCP · AWS Advanced Security · OWASP Top 10 · CNSS

---

## 📊 GitHub

![Sagar's GitHub stats](https://github-readme-stats.vercel.app/api?username=sagarbanwa&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sagarbanwa&layout=compact&hide_border=true)

---

<sub>All security testing referenced above was performed under authorized disclosure programs
or bug bounty scope.</sub>
