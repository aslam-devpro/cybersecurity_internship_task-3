# 🛡️ Cybersecurity Internship - Task 3

## 🔍 Basic Vulnerability Scan on Local Machine
📅 **Scan Date:** Aug 16, 2025  
🧰 **Tool Used:** Nessus Essentials  
🎯 **Target:** 127.0.0.1 (Kali local machine)  
⏳ **Scan Type:** Full vulnerability scan  

---

## 📊 Summary of Results

| Severity  | Count |
|-----------|-------|
| **Critical** | 2 |
| **High**     | 3 |
| **Medium**   | 2 |
| **Low / Info** | 73 |

> 💡 **Total Vulnerabilities Detected:** 80

---

## 🚨 Critical Vulnerabilities Identified

| Vulnerability Name | Suggested Fix |
|--------------------|----------------|
| **Node.js 18.x < 18.19.1 / 20.x < 20.11.1 / 21.x < 21.6.2 Multiple Vulnerabilities (Wednesday February 14 2024 Security Release)** | Upgrade to Node.js version 18.19.1 / 20.11.1 / 21.6.2 or later |
| **Node.js 20.x < 20.19.4 / 22.x < 22.17.1 / 24.x < 24.4.1 Multiple Vulnerabilities (Tuesday, July 15, 2025 Security Releases)** | Upgrade to Node.js version 20.19.4 / 22.17.1 / 24.4.1 or later |

---

## ✅ General Recommendations

- Apply all available updates and patches for Node.js and other affected packages.
- Regularly update system packages using the package manager (`apt update && apt upgrade`).
- Remove unused services and software to reduce attack surface.
- Enable automatic updates where possible to minimize exposure to future vulnerabilities.
- Perform regular vulnerability scans to monitor new risks.

---

## 📷 Screenshots

- 🔸 **Screenshot 1:** Nessus severity summary dashboard (showing Critical/High/Medium counts)  
- 🔸 **Screenshot 2&3:** Detailed view of two critical vulnerability

---

## 📌 Notes

- This scan was conducted on the local Kali machine using Nessus Essentials.
- Only the most significant vulnerabilities (critical/high) have been summarized here.
- A full detailed report is available in `scan_report.pdf`.

---

