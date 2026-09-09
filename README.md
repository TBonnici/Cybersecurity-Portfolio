# Cybersecurity-Portfolio
# [Your Name] | Data Security Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://linkedin.com/in/your-profile)
[![Email](https://img.shields.io/badge/Contact-Email-red?style=flat&logo=gmail)](mailto:your.email@example.com)
**Location:** Lake Orion, MI | **Open to Relocation:** Metro Detroit (Troy, Royal Oak, Clarkston), Colorado, Arizona

Entry-level data security analyst with hands-on experience in log analysis, SOC alert triage, network traffic investigation, and data normalization. 

---

### Technical Toolset
* **Security & Risk:** Incident Triage, Vulnerability Assessment, NIST SP 800-30, Risk Matrices, Malware Hash Identification.
* **Networking:** TCP/IP 3-Way Handshake, DoS/SYN Flood Analysis, Protocol Triage.
* **Systems & Admin:** Linux OS, MySQL, Access Control (RBAC, MFA), Encryption (TLS).
* **Data Analytics:** SQL (Filtering, Wildcards, Boolean Logic), Excel/Google Sheets (Data Normalization, Multi-Year Statistical Modeling), Data Cleaning.

---

### Featured Projects

#### 1. Security Logging: SQL Data Filtering & Threat Hunting
* **Objective:** Query security logs to isolate unauthorized access attempts outside of business hours and expected geographic regions.
* **Methodology:** Applied SQL `WHERE` clauses, boolean operators (`AND`, `OR`, `NOT`), and wildcards (`%`) to extract specific security events from the `log_in_attempts` and `employees` databases[cite: 2].
* **Key Artifacts:** [View SQL Queries & Log Analysis](./sql-log-analysis/)

#### 2. Security Operations: Phishing & Malware Alert Triage
* **Objective:** Investigate and escalate a medium-severity endpoint alert involving a malicious payload.
* **Methodology:** Analyzed a spoofed email header, identified the malicious password-protected attachment `bfsvc.exe`, and verified the threat against a known malicious file hash before escalating the ticket to a Level-Two SOC Analyst[cite: 3].
* **Key Artifacts:** [View Incident Ticket & Documentation](./soc-alert-triage/)

#### 3. Network Traffic Analysis: SYN Flood DoS Investigation
* **Objective:** Diagnose a network interruption causing server connection timeouts.
* **Methodology:** Analyzed the TCP three-way handshake process to determine that a malicious actor overwhelmed the web server's resources by flooding it with incomplete SYN packets[cite: 8]. 
* **Key Artifacts:** [View Network Traffic Incident Report](./network-traffic-analysis/)

#### 4. Risk Management: Server Vulnerability Assessment
* **Objective:** Evaluate the security posture and access controls of a critical business database.
* **Methodology:** Utilized the NIST SP 800-30 Rev. 1 framework to assess a Linux/MySQL server environment, calculating a formal risk matrix based on threat likelihood and business severity[cite: 12]. 
* **Remediation:** Recommended enforcing role-based access controls, TLS data encryption, and IP allow-listing[cite: 12].
* **Key Artifacts:** [View Vulnerability Assessment Report](./vulnerability-assessment/)

#### 5. Data Analytics: Multi-Year League Performance Modeling
* **Objective:** Transform unstructured performance data into a normalized, filterable relational dataset to scout capabilities and project trends.
* **Methodology:** Standardized multi-year records (one row per entity per season) to build interactive summary views, demonstrating proficiency in data hygiene and tabular structuring.
* **Key Artifacts:** [View Comprehensive Analytics Spreadsheet](./data-analytics/)
