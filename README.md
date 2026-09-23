# Cybersecurity Lab Tasks (CK)

This repository contains lab documentation and security assessment reports completed as part of the intermediate Cybersecurity course coursework.

---

## 📋 Course Assignments & Tasks

### 1. OWASP Juice Shop Vulnerability Assessment
A comprehensive analysis of the intentionally vulnerable OWASP Juice Shop web application.
* **Objective:** Set up the local application environment, discover security flaws, and execute controlled exploits across multiple risk categories.
* **Exploits Covered:**
  * SQL Injection (SQLi)
  * Broken Access Control / Privilege Escalation
  * Cross-Site Scripting (XSS)
  * Sensitive Data Exposure & Unprotected Endpoints
* **Deliverable:** Detailed lab report (`Task_1_OWASP Juice Shop Vulnerability Assessment.docx`) including attack vector breakdowns, proof-of-concept screenshots, and remediation strategies.

---

### 2. Wireshark Network Traffic & Protocol Analysis
An in-depth network packet capture and protocol evaluation using Wireshark.
* **Objective:** Capture live local network traffic, filter specific protocol suites, and evaluate security risks associated with cleartext transmissions.
* **Protocols Analyzed:** HTTP, DNS, TCP, and ICMP/ARP.
* **Key Observations:** Packet-by-packet breakdown of network exchanges, identification of unencrypted data flows, and security recommendations for encrypting transport layers (TLS/HTTPS).
* **Deliverable:** Traffic analysis report (`Task_2_Wireshark_Analysis.docx`) with annotated packet captures and security findings.

---

## 📁 Repository Structure

```text
├── Task_1_OWASP Juice Shop Vulnerability Assessment.docx
├── Task_2_Wireshark_Analysis.docx
└── README.md
