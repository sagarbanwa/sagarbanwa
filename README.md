# Hi, I'm Sagar Banwa 👋

**Offensive Security Engineer · Red Teamer · Bug Bounty Hunter**
IBM Cloud Platform Red Team · OSCP · Bengaluru, India

I break web apps, APIs, and cloud platforms — and increasingly AI/LLM systems — then help
teams fix them. Published CVEs, the tooling I hunt with, and credited in 25+ vendor security
acknowledgments including Apple, Google, the United Nations, Nokia, Dell, and Sony.

- 🔭 **Now:** Red Team @ IBM Cloud Platform — offensive assessments of cloud infrastructure and services
- 🧭 **Before:** SecOps Engineer @ Netreo (a BMC company) · Siemens
- 🎓 REVA University, Bengaluru (2013–2016)
- 🛡️ **Focus:** web/API pentesting, authorization & business-logic flaws, cloud attack surface, AI/LLM security
- 🎯 **Bug bounty:** [HackerOne](https://hackerone.com/) · [Bugcrowd](https://bugcrowd.com/h/sagarbanwa1337) · YesWeHack · Yogosha · Intigriti
- 📫 [LinkedIn](https://www.linkedin.com/in/sagarbanwa/)

---

## 🐞 Published CVEs & Advisories

| CVE | Product | Class | Reference | Writeup |
|---|---|---|---|---|
| **CVE-2020-29240** | LEPTON CMS 4.7.0 | Stored XSS (`URL` field, Pages) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2020-29240) · [EDB-49137](https://www.exploit-db.com/exploits/49137) | [writeup](advisories/CVE-2020-29240-lepton-cms.md) |
| **CVE-2023-46391** | WEBIGniter v28.7.23 | Stored XSS (Categories) | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2023-46391) · [EDB-51807](https://www.exploit-db.com/exploits/51807) | [writeup](advisories/CVE-2023-46391-webigniter.md) |
| *(no CVE)* | Grav CMS 1.6.30 + Admin 1.9.18 | Persistent XSS (`Page Title`) | [EDB-49264](https://www.exploit-db.com/exploits/49264) | [writeup](advisories/grav-cms-1.6.30-xss.md) |
| *(no CVE)* | mojoPortal Forums 2.7.0.0 | Persistent XSS (forum `Title`) | [EDB-49184](https://www.exploit-db.com/exploits/49184) | [writeup](advisories/mojoportal-2.7.0.0-xss.md) |

📚 **Google Hacking Database (GHDB):** Google dorks published to Exploit-DB for exposed-config
and sensitive-file discovery — e.g. [`pom.xml`](https://www.exploit-db.com/ghdb/8169),
[`auth.json`](https://www.exploit-db.com/ghdb/5762), [`/includes/OAuth2`](https://www.exploit-db.com/ghdb/5759).

---

## 🏆 Security Acknowledgments & Halls of Fame

| Organization | Recognition | Link |
|---|---|---|
| **Apple** | Web server security acknowledgements, 2021–2022 | [support.apple.com](https://support.apple.com/en-us/102812) |
| **United Nations** | UN Information Security Hall of Fame (2020) | [unite.un.org](https://unite.un.org/en/un-information-security-hall-fame) |
| **UNICEF** | Information Security Hall of Fame | [unicef.org](https://www.unicef.org/digitalimpact/unicef-information-security-hall-fame) |
| **Google** | Vulnerability Reward Program — honorable mentions (2020) | [bughunters.google.com](https://bughunters.google.com/) |
| **Nokia** | Coordinated Vulnerability Disclosure Hall of Fame (2020) | [nokia.com](https://www.nokia.com/about-us/security/product-security-and-vulnerability-disclosure/hall-of-fame/) |
| **Dell** | Security Hall of Fame (2019) | [dell.com/support/security](https://www.dell.com/support/security/en-us) |
| **Sony** | Hall of Thanks (2016) | [sony.com](https://www.sony.com/en/SonyInfo/Security/) |
| **NCIIPC (India)** | Hall of Fame — Top 15 researchers (Jan 2020) | [nciipc.gov.in](https://nciipc.gov.in/) |
| **EC-Council** | Hall of Fame + certificate of recognition | [eccouncil.org](https://www.eccouncil.org/) |

<sub>Links point to each program's disclosure page; dated entries above may have rotated off
vendors' annually-published lists. Full timeline with screenshots on
<a href="https://www.linkedin.com/in/sagarbanwa/">LinkedIn</a>.</sub>

<details>
<summary><b>Additional acknowledgments</b> (25+ total)</summary>

UN Women · Zynga · Takeaway.com · Socrata · Compass · B&H Photo Video · Moneytree ·
Avira · Lenovo · Adaware · Intel (×3) · ESET · Proto (University of Twente)

</details>

**Bug bounty payouts:** YesWeHack — accepted High-severity report ($400), Medium-severity
report (rank #330). Additional paid reports across HackerOne / Bugcrowd / Yogosha private programs.

---

## 🤖 AI / LLM Security

Where I'm putting research time now — as agents gain real capabilities, offensive-security
rigor is what keeps them safe to ship.

- **Bastion** *(in development)* — a defense-in-depth web/API security-assessment agent built
  on the principle *escalate every datum, never assume a surface is safe*: coverage-anchored
  flow, per-vuln-class deep-hunt modules, adversarial self-review.
- Interested in: prompt injection, tool/agent abuse, insecure output handling, vector-store
  BOLA, leaked-key scope abuse, and SSRF via model tooling.

---

## ✅ Responsible Disclosure & Authorized Use

I conduct offensive security work as a professional, under authorization, aligned with the
expectations of programs such as **Anthropic's Cyber Verification Program (CVP)** for
legitimate dual-use security research:

- **Authorization first** — every engagement is covered by a bug bounty program scope, a
  published Vulnerability Disclosure Policy, or a written client contract. No unauthorized testing.
- **Coordinated disclosure** — findings are reported privately to the vendor and kept
  confidential through remediation / standard embargo windows (typically 90 days) before any
  public writeup or PoC.
- **Non-destructive** — I prove impact with a minimal PoC; I don't exfiltrate user data, pivot
  beyond scope, or degrade availability.
- **Prohibited-use line** — I don't build or assist ransomware, malware for illegal use, mass
  data theft, or attacks on systems I'm not authorized to test.
- **Verifiable identity** — IBM Cloud Platform Red Team; OSCP (Offensive Security);
  [LinkedIn](https://www.linkedin.com/in/sagarbanwa/). Available for organizational reference checks.

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

## 🛠️ Toolbox & Credentials

**Offensive:** Burp Suite Pro · nuclei · ffuf · sqlmap · ProjectDiscovery suite
(subfinder/httpx/dnsx/naabu/katana/tlsx) · Frida · Objection · nmap · Metasploit
**Cloud:** AWS · IBM Cloud · Azure · container / Kubernetes security
**Certifications:** OSCP · AWS for Architects: Advanced Security · Microsoft Cybersecurity
Stack: Advanced Identity & Endpoint Protection · ICSI CNSS · OWASP Top 10

---

## 📊 GitHub

![Sagar's GitHub stats](https://github-readme-stats.vercel.app/api?username=sagarbanwa&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sagarbanwa&layout=compact&hide_border=true)

---

<sub>All security testing referenced here was performed under authorized disclosure programs,
published VDPs, or written client engagements.</sub>
