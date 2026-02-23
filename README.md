# Cybersecurity Portfolio
## Elijah Bastien | B.S. Computer Science (Information Security)

This repository contains a collection of hands-on projects documenting my experience in network security, incident response, security automation, and compliance auditing. 

---

## 🛠️ Technical Skills & Tools
* **Security:** Threat Detection, Incident Response, Risk Assessment (NIST SP 800-30), SIEM.
* **Automation/Data:** Python (File I/O, Data Cleaning), SQL (Security Filtering).
* **Networking:** TCP/IP, DNS, Packet Analysis (tcpdump, Wireshark).
* **Systems:** Linux (CLI, Permissions), Windows, IAM (Least Privilege).

---

## 📂 Project Directory

### 🐍 Security Automation & Data Analysis
1.  **[Python: Automated Access Control Update](./Python_Algorithm_File_Updates.md)**
    * **The Problem:** Manual updates to "allow lists" are slow and prone to human error.
    * **The Solution:** Developed a Python algorithm that parses a text file of IP addresses, identifies unauthorized users via a `remove_list`, and updates the file using `.split()`, `.join()`, and context managers.
    * **Skills:** Python, Automation, File Handling.

2.  **[SQL: Security Event Investigation](./SQL_Filters_Investigation.md)**
    * **The Problem:** Analyzing large log files for suspicious after-hours activity.
    * **The Solution:** Applied SQL filters (`AND`, `OR`, `NOT`, `LIKE`) to identify failed login attempts occurring after 18:00 and track device updates across departments.
    * **Skills:** SQL, Database Security, Log Analysis.

### 🕵️ Incident Response & Network Defense
3.  **[Network Analysis: SYN Flood DoS Attack](./SYN_Flood_Report.md)**
    * **Insight:** Analyzed server logs to identify a SYN Flood attack. Documented the exploitation of the TCP three-way handshake and recommended firewall rate-limiting rules.
    * **Skills:** TCP/IP, DoS Mitigation, Incident Reporting.

4.  **[SOC Operations: Incident Handler's Journal](./Incident_Journal.md)**
    * **Insight:** A detailed log of responding to a healthcare ransomware incident and a financial services phishing attempt. Utilized **VirusTotal** for SHA256 hash verification and followed specialized playbooks.
    * **Skills:** Malware Analysis, VirusTotal, Incident Life Cycle (NIST).

5.  **[Network Traffic: DNS & UDP Troubleshooting](./Network_Traffic_Analysis.md)**
    * **Insight:** Used `tcpdump` to diagnose a "Destination Port Unreachable" error. Identified UDP Port 53 (DNS) failure and recommended firewall/server configuration fixes.
    * **Skills:** Packet Sniffing, tcpdump, DNS Security.

### 🛡️ System Hardening & Access Control
6.  **[Linux: Filesystem Permissions Audit](./Linux_Permissions.md)**
    * **Insight:** Performed a security audit on a research directory. Used `chmod` to enforce the Principle of Least Privilege on hidden files and project directories.
    * **Skills:** Linux CLI, Access Control (IAM), System Hardening.

7.  **[Brute Force Remediation & Malware Defense](./Brute_Force_Report.md)**
    * **Insight:** Investigated a successful brute-force attack on a web server. Analyzed the injection of malicious JavaScript and recommended IAM policy changes and password complexity requirements.
    * **Skills:** Web Security, Brute Force Mitigation, Password Policy.

### 📋 Risk Management & Compliance
8.  **[Compliance Audit: Botium Toys](./Botium_Toys_Audit.md)**
    * **Insight:** Evaluated a retail organization's posture against **PCI DSS**, **GDPR**, and **SOC type 2**. Identified gaps in encryption and disaster recovery.
    * **Skills:** Auditing, Compliance Frameworks, Data Privacy.

9.  **[NIST Risk Register & Assessment](./Risk_Register.md)**
    * **Insight:** Conducted a formal risk assessment for a financial institution. Calculated risk priority scores (Likelihood x Severity) for Business Email Compromise (BEC) and physical theft.
    * **Skills:** Risk Management, NIST Framework, Qualitative Analysis.

10. **[Vulnerability Assessment: MySQL Server](./Vulnerability_Assessment.md)**
    * **Insight:** Assessed a marketing database server for vulnerabilities. Recommended transitioning from SSL to TLS and implementing MFA and Role-Based Access Control (RBAC).
    * **Skills:** Vulnerability Management, Database Hardening.

---

## 📈 Security Awareness Data
I also focus on the human element of security. I developed a **Phishing Click-Rate Visual Dashboard** to identify high-risk departments (e.g., Media Relations vs. Global Security) to help organizations target their security training effectively.

---

### 📫 Contact Information
* **Email:** ecb0523@gmail.com
* **Education:** SNHU (Class of 2026)
