# 🔵 SOC Analyst Home Lab

## Overview
This project is a hands-on **SOC Analyst Home Lab** designed to simulate real-world security monitoring, detection, and incident investigation in an enterprise-style environment. The lab focuses on centralized logging, alert creation, attacker activity detection, and structured incident response workflows using a SIEM.

The objective is to demonstrate practical **Blue Team skills** relevant to SOC Analyst and Junior Security Engineer roles.

---

## 🎯 Project Objectives
- Build a centralized logging and monitoring environment
- Detect common attack techniques using SIEM alerts
- Analyze and investigate security events
- Map detections to the MITRE ATT&CK framework
- Document findings and mitigation strategies

---

## 🏗️ Lab Architecture

### Systems Used
- **Windows Server** – Authentication, system, and security logs
- **Windows 10** – Endpoint victim machine
- **Kali Linux** – Attacker machine
- **SIEM Platform** – Splunk or ELK Stack

### Architecture Flow

[Kali Linux Attacker]
|
v
[Windows 10 / Windows Server]
|
v
[SIEM]


---

## 🛠️ Tools & Technologies
- SIEM: Splunk / ELK Stack
- Endpoint Logging: Sysmon
- Operating Systems: Windows Server, Windows 10, Kali Linux
- Attack Simulation: Nmap, Metasploit
- Network Analysis: Wireshark
- Frameworks: MITRE ATT&CK

---

## 🔍 Attack Scenarios Simulated
The following attack techniques were safely simulated within an isolated lab environment to generate realistic security events:

- Brute-force login attempts
- Network scanning and enumeration
- Unauthorized access attempts
- Malicious PowerShell execution
- Suspicious process creation

---

## 🚨 Detection & Alerting

### Alerts Implemented
- Excessive failed authentication attempts
- Suspicious PowerShell activity
- Unusual process execution behavior
- Network scanning indicators

### Detection Methodology
- Event ID correlation
- Threshold-based alerting
- User and source behavior analysis
- Endpoint telemetry correlation using Sysmon

Each alert was mapped to relevant **MITRE ATT&CK techniques** to align detections with industry standards.

---

## 🕵️ Incident Investigation Workflow
1. Alert triggered in the SIEM
2. Initial triage and severity assessment
3. Log correlation and timeline analysis
4. Identification of attacker techniques
5. Documentation of findings
6. Mitigation and remediation recommendations

---

## 📊 Key Findings
- Brute-force attacks generated consistent authentication failure patterns
- Sysmon significantly improved endpoint visibility
- Correlating authentication and process events reduced false positives
- Centralized logging is critical for effective detection and investigation

---

## 🛡️ Mitigation & Recommendations
- Implement account lockout policies
- Enable PowerShell script block logging
- Harden endpoint security configurations
- Centralize logs across all critical systems
- Tune SIEM alert thresholds to reduce noise

---

## 📁 Repository Structure
SOC-Analyst-Home-Lab/
│── README.md
│── diagrams/
│── detections/
│── screenshots/
│── reports/


- **diagrams/** – Lab architecture visuals
- **detections/** – Detection logic and alert queries
- **screenshots/** – Evidence of alerts and investigations
- **reports/** – Incident analysis and documentation

---

## 📸 Evidence
Screenshots demonstrating alert creation, log analysis, and investigations are included in the `screenshots` directory to validate detection workflows and findings.

---

## 🧠 Skills Demonstrated
- SIEM monitoring and alerting
- Log analysis and correlation
- Incident triage and investigation
- Endpoint detection and visibility
- MITRE ATT&CK mapping
- Security documentation and reporting

---

## 📌 Disclaimer
All testing was conducted in a **controlled lab environment** for educational and defensive purposes only. No production systems were affected.

---
