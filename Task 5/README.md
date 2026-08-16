# Task 5 — Capstone Project & Incident Response
> ApexPlanet Cybersecurity & Ethical Hacking Internship | Days 49–60

![Task](https://img.shields.io/badge/Task-5%20of%205-blue)
![Timeline](https://img.shields.io/badge/Timeline-Days%2049--60-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Focus](https://img.shields.io/badge/Focus-DVWA%20Pentest%20%26%20IR-red)

---

## 🎯 Objective

Complete a full DVWA penetration testing capstone and document a practical incident response workflow including detection, containment, and eradication.

---

## 📁 Files in This Folder

| File/Folder | Description |
|------|-------------|
| [DVWA-Pentest-Task5](./DVWA-Pentest-Task5/) | Final capstone project package containing report, evidence, scripts, and docs |
| [README.md](./README.md) | This file |

---

## 🧪 Lab Setup

| Component | Details |
|-----------|---------|
| **Attacker OS** | Kali Linux |
| **Target VM** | Metasploitable2 with DVWA |
| **Attack Surface** | DVWA modules (SQLi, XSS, CSRF, File Inclusion) |
| **Network** | Isolated VirtualBox lab network |

---

## ✅ Activities Completed

### 1. End-to-End DVWA Pentest
- Executed vulnerability tests across DVWA security levels
- Collected evidence for SQL Injection, XSS, CSRF, LFI, and RFI
- Documented risk and impact in final report formats

### 2. Automated SQLi Validation
- Used `sqlmap` to enumerate databases and tables
- Saved proof outputs in the SQLi evidence folder

### 3. Incident Response Simulation
- Parsed Apache log data using `log_detection.py`
- Identified suspicious patterns and source activity
- Exported findings to CSV for reporting
- Recorded containment and eradication evidence

---

## 📦 Task 5 Project Structure

```text
Task 5/
├── README.md
└── DVWA-Pentest-Task5/
    ├── report/
    │   ├── DVWA_Pentest_Report.docx
    │   └── DVWA_Pentest_Report.pdf
    ├── diagrams/
    │   └── network_diagram.svg
    ├── scripts/
    │   └── log_detection.py
    ├── evidence/
    │   ├── sqli/
    │   ├── xss/
    │   ├── csrf/
    │   ├── file_inclusion/
    │   └── incident_response/
    ├── logs/
    │   └── sample_access.log
    └── docs/
        └── procedure.md
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| DVWA | Vulnerable web application for testing |
| sqlmap | Automated SQL injection testing |
| Burp Suite | Request interception and manipulation |
| Python | Log signature detection and IR support |
| Nmap/Nikto | Recon and web surface discovery |

---

## 📦 Deliverables

- [x] Final penetration testing report (DOCX + PDF)
- [x] Organized evidence per vulnerability category
- [x] Incident response findings CSV
- [x] Detection script and sample logs
- [x] Procedure documentation

---

## 🔗 Links

- 📹 **Video Walkthrough:** [Watch Here](https://www.linkedin.com/posts/mr-manivel-r_cybersecurity-ethicalhacking-penetrationtesting-ugcPost-7494772118019190784-2Vvy/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGDJA9sBzSi23edH7UWChoU_mcEMAARlJJ8)
- 📄 **Procedure Document:** [procedure.md](./DVWA-Pentest-Task5/docs/procedure.md)
- 🧠 **Detection Script:** [log_detection.py](./DVWA-Pentest-Task5/scripts/log_detection.py)
- 📂 **Evidence Folder:** [evidence](./DVWA-Pentest-Task5/evidence/)
- 📁 **Main Repo:** [apexplanet-cybersecurity-internship](https://github.com/manivel-cyber-ai/apexplanet-cybersecurity-internship)
- 🌐 **Portfolio:** [manivel-cyber-ai.github.io](https://manivel-cyber-ai.github.io)
- 💼 **LinkedIn:** [linkedin.com/in/mr-manivel-r](https://www.linkedin.com/in/mr-manivel-r/)

---

> ⚠️ All activities were performed in an isolated lab environment for educational purposes only.

*Manivel R | ApexPlanet Internship 2026 | Anna University*
