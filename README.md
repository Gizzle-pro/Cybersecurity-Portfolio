# Cybersecurity Hands-On Portfolio

**Gizzle Montemayor**  
📍 Davao Region, Philippines | ✉️ my.freeup@gmail.com
🔗 **LinkedIn:** www.linkedin.com/in/gizzlesaygo 
🛡️ **TryHackMe Profile:** https://tryhackme.com/p/DTiger?utm_campaign=social_share&utm_medium=social&utm_content=profile&cardVersion=d149e8c75b4a&utm_source=copy&share_date=2026-11-12&sharerId=6a4c735f0e6c2287c48611c5  

---

## 🎯 Professional Objective
Detail-oriented IT and Cybersecurity Specialist equipped with a **B.S. in Computer Science**, a **B.S. in Psychology**, and advanced studies in **Cybersecurity & AI**. Proven hands-on experience in **SIEM log analysis**, **incident triage**, and **web application vulnerability assessments** developed through rigorous lab environments and simulated SOC operations. Seeking an entry-level **L1 SOC Analyst** or **Junior Penetration Tester** role offering visa sponsorship and international relocation.

---

## 🛠️ Technical Toolkit

| Category | Skills & Tools |
| :--- | :--- |
| **Defensive & SIEM** | Splunk, Microsoft Sentinel, Log Triage, Incident Response, Event Log Analysis (Windows Sysmon / Linux Auth) |
| **Offensive & Analysis** | Nmap, Burp Suite, Wireshark, Metasploit, OWASP Top 10, Web App Testing |
| **Development & Systems** | Python, SQL, C, Java, PHP, Linux/Unix Administration, Database Architecture |
| **Practices & Frameworks**| MITRE ATT&CK, NIST SP 800-61 (Incident Handling), Cyber Kill Chain |

---

## 📜 Key TryHackMe Learning Paths Completed
- [x] **SOC Level 1 Path:** SIEM query construction, log analysis, digital forensics, alert triage.
- [x] **Jr Penetration Tester Path:** Network scanning, privilege escalation, web application exploitation.
- [x] **Cyber Defense Path:** Threat intelligence, malware analysis concepts, network security monitoring.

---

## 📁 Featured Security Projects & Lab Write-ups

### 🛡️ Defensive Security & Incident Response (SOC Analyst)

#### 1. [Splunk SIEM Investigation: Windows Domain Controller Brute-Force](./SOC-Analyst-Incident-Reports/Incident-01-Splunk-BruteForce.md)
* **Objective:** Investigate suspicious login activity using Splunk search queries to identify malicious authentication attempts.
* **Key Actions:** 
  * Filtering Event Code `4625` (Failed Logon) vs. Event Code `4624` (Successful Logon).
  * Isolated source IP addresses, targeted user accounts, and constructed a chronological attack timeline.
* **Deliverable:** [View Full Incident Report](./SOC-Analyst-Incident-Reports/Incident-01-Splunk-BruteForce.md) (Includes timeline, query strings, and remediation steps).

---

### ⚔️ Offensive Security & Vulnerability Assessments (Ethical Hacking)

#### 1. [Web Application Vulnerability Assessment – TryHackMe (Vulnversity)](./Ethical-Hacking-Assessments/Assessment-01-Vulnversity-Report.md)
* **Objective:** Perform end-to-end vulnerability assessment and exploitation on a target Linux web server.
* **Key Actions:** 
  * Network discovery using `nmap` and web directory fuzzing via `gobuster`.
  * Identified unrestricted file upload vulnerability, bypassed PHP file extension filters, and established a reverse shell.
  * Executed privilege escalation leveraging misconfigured SUID binaries (`systemctl`).
* **Deliverable:** [View Vulnerability Assessment Report](./Ethical-Hacking-Assessments/Assessment-01-Vulnversity-Report.md) (Includes remediation recommendations for software patch/hardening).

---

## 📈 GitHub Repository Structure
```text
├── README.md
├── SOC-Analyst-Incident-Reports/
│   └── Incident-01-Splunk-BruteForce.md
└── Ethical-Hacking-Assessments/
    └── Assessment-01-Vulnversity-Report.md
