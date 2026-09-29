# 🛡️ Penetration Testing & Web Security Portfolio

> Hands-on vulnerability assessment reports and penetration testing write-ups — created during training at **NTI Cyber Academy** and independent lab research.

[![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-557C94?style=flat&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Burp Suite](https://img.shields.io/badge/Tool-Burp%20Suite-orange?style=flat)](https://portswigger.net/burp)
[![OWASP](https://img.shields.io/badge/OWASP-Top%2010-red?style=flat)](https://owasp.org/www-project-top-ten/)
[![Metasploit](https://img.shields.io/badge/Framework-Metasploit-blue?style=flat)](https://www.metasploit.com/)

## 📖 Overview

This repository documents my practical journey in **Web Application Security** and **Network Penetration Testing**. Each report follows a professional methodology:

- Executive Summary with risk severity ratings
- Step-by-step Proof of Concept (PoC) with screenshots
- Technical impact analysis
- Remediation & mitigation recommendations

All testing was performed **legally in isolated lab environments** (DVWA, OWASP Juice Shop, Metasploitable 2).

---

## 📁 Repository Structure

```text
Penetration-Testing-Reports/
├── Dvwa labs/
│   ├── DVWA-Pentest-ReportBySeifeldeen.pdf
│   ├── DVWA-API-By-Seif-eldeen.pdf
│   └── Report-By-Seif-eldeen.pdf
├── juice shop/
│   └── juice-shop-by-seif.pdf
├── Metasploitable 2/
│   └── report-by-seif.pdf
├── certifcations/
│   ├── THM-pre-securtiy.png
│   ├── computer-network-fun.jpeg
│   ├── into-net-sec.jpeg
│   ├── into-to-cybersecurtiy-cisco.pdf
│   └── nti-cyber-academy-pentset-appsec.pdf.png
└── README.md
```

---

## 🧪 Practical Lab Reports

### 1. DVWA — Damn Vulnerable Web Application

**Scope:** Web Application Security & OWASP Top 10 Assessment

**Vulnerabilities Tested:** XSS (Reflected / Stored / DOM), SQL Injection, Command Injection, File Inclusion (LFI/RFI), File Upload, Broken Access Control, API Security

**Reports:**
- [DVWA Full Pentest Report](./Dvwa%20labs/DVWA-Pentest-ReportBySeifeldeen.pdf)
- [DVWA API Security Assessment](./Dvwa%20labs/DVWA-API-By-Seif-eldeen.pdf)
- [DVWA Additional Report](./Dvwa%20labs/Report-By-Seif-eldeen.pdf)

### 2. OWASP Juice Shop

**Scope:** Modern Web Application & API Security Testing

**Vulnerabilities Tested:** OWASP Top 10, Broken Authentication, Broken Access Control, Security Misconfiguration, Sensitive Data Exposure

**Report:**
- [Juice Shop Assessment](./juice%20shop/juice-shop-by-seif.pdf)

### 3. Metasploitable 2

**Scope:** Network Penetration Testing & System Security

**Focus Areas:** Network Reconnaissance, Service Enumeration, Port Scanning, System Exploitation, Privilege Escalation

**Report:**
- [Metasploitable 2 Network Pentest Report](./Metasploitable%202/report-by-seif.pdf)

---

## 🎓 Certifications & Training

| Certification / Course | Issuer | Proof |
|---|---|---|
| Pre Security Learning Path | TryHackMe | [THM-pre-securtiy.png](./certifcations/THM-pre-securtiy.png) |
| Computer Network Fundamentals | — | [computer-network-fun.jpeg](./certifcations/computer-network-fun.jpeg) |
| Introduction to Network Security | — | [into-net-sec.jpeg](./certifcations/into-net-sec.jpeg) |
| Introduction to Cybersecurity | Cisco | [into-to-cybersecurtiy-cisco.pdf](./certifcations/into-to-cybersecurtiy-cisco.pdf) |
| Penetration Testing & AppSec | NTI Cyber Academy | [nti-cyber-academy-pentset-appsec.pdf.png](./certifcations/nti-cyber-academy-pentset-appsec.pdf.png) |

> 💡 Tip: Rename folder `certifcations` → `certifications` to fix the typo. GitHub: `git mv certifcations certifications`

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| **Web Proxy & Assessment** | Burp Suite, OWASP ZAP |
| **Recon & Enumeration** | Nmap, Gobuster, Netcat, Nikto |
| **Exploitation** | Metasploit Framework |
| **Lab Environment** | Kali Linux, VirtualBox, DVWA, OWASP Juice Shop, Metasploitable 2 |

---

## 📝 Report Methodology

Every report in this repo follows this structure:

1. **Executive Summary** — scope, approach, high-level findings
2. **Severity Ratings** — Critical / High / Medium / Low with CVSS-style reasoning
3. **Proof of Concept** — reproducible steps + screenshots / payloads
4. **Impact Analysis** — what an attacker could achieve
5. **Remediation** — short-term fix + long-term hardening

---

## 🎯 Skills Demonstrated

- OWASP Top 10 testing (2021)
- Manual web exploitation + Burp Suite workflow
- Network scanning, enumeration & exploitation
- Linux privilege escalation basics
- Professional security report writing

---

## ⚠️ Legal Disclaimer

All reports are for **educational purposes only**. Testing was conducted exclusively on intentionally vulnerable local lab machines. Do not attempt these techniques on systems you do not own or have explicit written permission to test.

---

## 👤 Author

**Seif Eldeen (TermnaitorX0)**

- GitHub: [@TermnaitorX0](https://github.com/TermnaitorX0)
- Training: NTI Cyber Academy — Penetration Testing & AppSec
- Interests: Web Security, Bug Bounty, Network Pentesting

> Open to internships, junior pentest roles, and bug bounty collaboration.

---

⭐ If you find this portfolio useful, consider starring the repo!
# 🛡️ Penetration Testing & Web Security Portfolio

Welcome to my cybersecurity lab repository. This repository contains detailed technical vulnerability assessment reports and penetration testing write-ups created during my training at **NTI Cyber Academy** and independent security research.


## 📁 Practical Lab Reports

### 1.  DVWA (Damn Vulnerable Web Application)
* **Scope:** Web Application Security & OWASP Top 10 Assessment.
* **Vulnerabilities Tested:** Cross-Site Scripting (XSS), SQL Injection (SQLi), Command Injection, File Inclusion, Broken Access Control, and API Security.
* **Document:** View DVWA Lab 

### 2.  OWASP Juice Shop
* **Scope:** Modern Web Application & API Security Testing.
* **Vulnerabilities Tested:** OWASP Top 10, Broken Authentication, Broken Access Control, and Security Misconfigurations.
* **Document:**   juice shop

### 3.  Metasploitable 2
* **Scope:** Network Penetration Testing & System Security.
* **Focus Areas:** Network Reconnaissance, Service Enumeration, Port Scanning, System Exploitation, and Privilege Escalation.
* **Document:** Metasploitable 2/report-by-seif.pdf


##  Tools & Technologies Used
* **Web Security Assessment:** Burp Suite, OWASP ZAP.
* **Reconnaissance & Enumeration:** Nmap, Gobuster, Netcat.
* **Exploitation:** Metasploit Framework.
* **Environments & OS:** Kali Linux, VirtualBox.


##  Technical Report Structure
All reports follow a structured documentation methodology including:
* Executive Summary & Severity Risk Ratings
* Step-by-Step Proof of Concept (PoC)
* Technical Impact Analysis
* Mitigation & Remediation Guidelines
