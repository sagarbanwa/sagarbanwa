# Hi, I'm Sagar Banwa 👋

**Offensive Security Engineer · Red Teamer · Bug Bounty Hunter**
IBM Cloud Platform Red Team · OSCP · Bengaluru, India

I break web apps, APIs, and cloud platforms — and increasingly AI/LLM systems — then help
teams fix them. I've published CVEs, written the tooling I hunt with, and been credited in
vendor security acknowledgments including Apple's.

- 🔭 **Now:** Red Team @ IBM Cloud Platform — offensive assessments of cloud infrastructure and services
- 🛡️ **Focus:** web/API pentesting, authorization & business-logic flaws, cloud attack surface, AI/LLM security
- 🧰 **I build:** recon and bug-bounty automation (see pinned repos)
- 🎯 **Bug bounty:** [HackerOne](https://hackerone.com/) · [Bugcrowd](https://bugcrowd.com/h/sagarbanwa) · Yogosha · YesWeHack · Intigriti
- 📫 [LinkedIn](https://www.linkedin.com/in/sagarbanwa/)

---

## 🐞 Published CVEs & Advisories

| CVE | Product | Class | Reference | Writeup |
|---|---|---|---|---|
| **CVE-2020-29240** | LEPTON CMS 4.7.0 | Stored XSS (`URL` field, Pages) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2020-29240) · [EDB-49137](https://www.exploit-db.com/exploits/49137) | [writeup](advisories/CVE-2020-29240-lepton-cms.md) |
| **CVE-2023-46391** | WEBIGniter v28.7.23 | Stored XSS (Categories) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2023-46391) · [EDB-51807](https://www.exploit-db.com/exploits/51807) | [writeup](advisories/CVE-2023-46391-webigniter.md) |
| *(no CVE)* | Grav CMS 1.6.30 + Admin 1.9.18 | Persistent XSS (`Page Title`) | [EDB-49264](https://www.exploit-db.com/exploits/49264) | [writeup](advisories/grav-cms-1.6.30-xss.md) |
| *(no CVE)* | mojoPortal Forums 2.7.0.0 | Persistent XSS (forum `Title`) | [EDB-49184](https://www.exploit-db.com/exploits/49184) | [writeup](advisories/mojoportal-2.7.0.0-xss.md) |

📚 **Google Hacking Database (GHDB):** multiple Google dorks published to Exploit-DB for
exposed-config and sensitive-file discovery — e.g. [`pom.xml`](https://www.exploit-db.com/ghdb/8169),
[`auth.json`](https://www.exploit-db.com/ghdb/5762), [`/includes/OAuth2`](https://www.exploit-db.com/ghdb/5759).

> Reported vulnerabilities to India's **NCIIPC** (National Critical Information Infrastructure
> Protection Centre) responsible-disclosure program.

---

## 🏆 Security Acknowledgments

- **Apple** — web server security acknowledgements, [2021–2022](https://support.apple.com/en-us/102812)
- **Tidepool** — Hall of Fame
- Additional vendor halls of fame — *links added as confirmed*

---

## 🤖 AI / LLM Security

Where I'm putting research time now — as agents gain real capabilities, offensive-security
rigor is what makes them safe to ship.

- **Bastion** *(in development)* — a defense-in-depth web/API security-assessment agent built
  on the principle *escalate every datum, never assume a surface is safe*: coverage-anchored
  flow, per-vuln-class deep-hunt modules, adversarial self-review.
- Interested in: prompt injection, tool/agent abuse, insecure output handling, vector-store
  BOLA, leaked-key scope abuse, and SSRF via model tooling.

---

## 🧰 Open-Source Tooling

| Repo | What it does |
|---|---|
| [`BountySleuth`](https://github.com/sagarbanwa/BountySleuth) | Browser-extension web scanner — WAF fingerprinting, CORS/XSS/CSRF/DOM analysis, source-map unpacking, AEM deep scan, dependency-confusion & cache-deception checks |
| [`checklist-BB`](https://github.com/sagarbanwa/checklist-BB) | Bug bounty methodology checklist |
| [`Subsonly`](https://github.com/sagarbanwa/Subsonly) | Subdomain enum (subfinder + amass + assetfinder) filtered to live hosts with httpx |
| [`CIDR`](https://github.com/sagarbanwa/CIDR) | Expand an org's CIDR ranges into scannable IP lists for httpx |
| [`Firebase-Security-Scanner`](https://github.com/sagarbanwa/Firebase-Security-Scanner) | Assessment tool for misconfigured Firebase projects |
| [`maxlim`](https://github.com/sagarbanwa/maxlim) | Subdomain discovery wrapper around ProjectDiscovery tooling |

---

## 🛠️ Toolbox

**Offensive:** Burp Suite Pro · nuclei · ffuf · sqlmap · ProjectDiscovery suite
(subfinder/httpx/dnsx/naabu/katana/tlsx) · Frida · Objection · nmap · Metasploit
**Cloud:** AWS · IBM Cloud · Azure · container / Kubernetes security
**Certs:** OSCP · AWS Advanced Security · OWASP Top 10 · CNSS

---

## 📊 GitHub

![Sagar's GitHub stats](https://github-readme-stats.vercel.app/api?username=sagarbanwa&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sagarbanwa&layout=compact&hide_border=true)

---

<sub>All security testing referenced here was performed under authorized disclosure programs
or bug bounty scope.</sub>
