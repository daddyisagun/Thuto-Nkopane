<h1 align="center">Hi, I'm [Your Name] 👋</h1>
<h3 align="center">IT Support • IT Technician • Cybersecurity</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Work-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-IT%20%26%20Cybersecurity-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Location-[City,%20Country]-lightgrey?style=for-the-badge" />
</p>

## 👤 About Me

I'm a recent graduate of the **Zaio Cybersecurity Bootcamp** with a broad interest in IT and security. I enjoy solving problems, understanding how systems work, and helping people keep their technology running smoothly and safely.

I'm looking for an entry-level role in IT, such as **IT Support, IT Technician, Help Desk, Security Analyst or SOC Analyst**, where I can keep learning and contribute from day one.

- 🔭 Currently learning: [e.g. CompTIA A+, Security+, networking, cloud fundamentals]
- 🧪 I practise on: TryHackMe
- 💬 Ask me about: cybersecurity, troubleshooting, and how I approach problems

## 🚀 Projects

### 🚨 SOC Incident Response: Three Shift Reports
Triaged alerts, separated true positives from benign activity, built incident timelines and wrote containment and recovery plans.

- **Shift 1:** Dropper/loader on a workstation (a fake "design suite" zip leading to a masquerading process tree with a config file). Recommended isolation, process termination, fleet sweep and user interview.
- **Shift 2:** Full attack chain, from VPN password spray with no MFA, to LSASS credential dump, lateral movement to a domain controller, ~500 MB of finance data exfiltrated, and persistence (rogue admin account, SYSTEM scheduled task, RDP enabled). Every step mapped to MITRE ATT&CK.
- **Shift 3:** Ransomware spreading over SMB to three hosts. Traced patient zero to a dormant scheduled task left by an earlier intrusion, explained why the patch reboot only *triggered* it, and ordered containment by urgency (isolate, block C2, pause rollout, preserve evidence, remediate).

**Skills shown:** alert triage, timeline reconstruction, root cause analysis, containment planning, MITRE ATT&CK mapping, recommendations.

### 🦠 Malware Analysis: Static & Dynamic Report
Analysed a provided Windows .NET sample (identified via VirusTotal and MalwareBazaar as AsyncRAT/XWorm family) in an isolated VM.

- **Static:** file type by signature, MD5/SHA-1/SHA-256, PE headers and compile timestamp, section entropy, import table, and strings (found an anti-sandbox hosting check). Concluded the sample used managed-code obfuscation rather than a native packer.
- **Dynamic:** isolated Windows 10 VM with a clean snapshot, host-only networking, and System Informer, Wireshark and Regshot monitoring. When no execution was observed, I troubleshot the lab (.NET runtime) and documented two confidence-rated explanations rather than overclaiming.
- **Output:** IoC table, STIX 2.1 bundle, ATT&CK mapping, detection recommendations.

**Skills shown:** safe malware handling, PE analysis, hashing and reputation lookups, IoC extraction, STIX 2.1, honest reporting of limitations.

### 🛒 Web Application Penetration Test: NahamStore
Tested an e-commerce lab environment (TryHackMe) against the OWASP Top 10 and delivered an executive-style findings deck with a remediation roadmap.

- **10 confirmed findings (7 High, 3 Medium):** reflected and stored XSS, two open redirects, two IDORs, CSRF with an unenforced token, SSRF with a filter bypass, LFI via path traversal, and XXE.
- Showed how open redirect, IDOR and stored XSS **chain** into account takeover and data exposure.
- Each finding includes the request, payload, business impact, CWE/OWASP mapping and a specific fix, plus a 7 / 30 / 90-day roadmap.

**Tools:** Burp Suite, subfinder, ffuf, gobuster, Arjun, CyberChef

### 🏦 PyBank: Command-Line ATM System (Python)
A multi-module Python app with registration, login, deposits, withdrawals, transfers and statements.

- Object-oriented design split across account, transaction and main modules
- PIN hashing with SHA-256, input validation, a 3-attempt login limit, and CSV-based audit logs for logins and transactions

### 🐍 Python Practice
Small scripts that built my fundamentals: FizzBuzz, a tip calculator and a cheerleader program (loops, conditionals, string handling, user input).

## 🛡️ Key Skills

- **Incident response & triage:** alert triage, incident timelines, containment, root cause analysis
- **Malware analysis:** static and dynamic analysis, IoC extraction, STIX 2.1
- **Web application security testing:** OWASP Top 10, Burp Suite, remediation advice
- **Frameworks:** MITRE ATT&CK, OWASP, CWE
- **Troubleshooting & systems:** Windows and Linux virtual machines, lab setup, fault diagnosis
- **Python:** OOP, file handling, hashing, input validation
- **Reporting & communication:** clear reports for technical and non-technical readers

## 🧰 Tools

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat-square&logo=virtualbox&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square&logo=virustotal&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

Also used: System Informer (Process Hacker), Regshot, pefile, readpe, pescan, exiftool, MalwareBazaar, ffuf, gobuster, subfinder, Arjun, CyberChef, 7-Zip

## 🏆 Education & Training

- 🎓 Zaio Cybersecurity Bootcamp ([Year])
- 🧪 TryHackMe: History of Malware, Malware Introductory, Basics of Malware RE, Basic Static Analysis, Basic Dynamic Analysis, NahamStore
- 📜 [CompTIA Security+ / other certification: in progress or completed]

## 📫 Let's Connect

- 💼 [LinkedIn](your-linkedin-url)
- 📧 [your.email@example.com](mailto:your.email@example.com)
- 🧠 [TryHackMe Profile](your-tryhackme-url)
