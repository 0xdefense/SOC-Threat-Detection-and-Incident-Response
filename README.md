# 🛡️ SOC Threat Detection & Incident Response Project

## 📌 Overview

This project simulates the role of a Security Operations Center (SOC) Analyst. It involves analyzing system logs, detecting threats, performing alert triage, and investigating a multi-stage cyber attack using SIEM tools.

---

## 🎯 Objectives

* Analyze logs using Splunk SIEM
* Identify Indicators of Compromise (IOCs)
* Perform alert triage (True Positive / False Positive / Needs Investigation)
* Correlate logs and alerts
* Investigate a real-world attack scenario

---

## 🛠️ Tools Used

* Splunk (SIEM)
* VirusTotal, IPVoid, URLVoid
* Nmap
* MXToolbox, NSLookup

---

## 📂 Project Structure

### 🟡 Week 1 – Log Analysis

* Identified brute-force login attempts
* Analyzed Windows Event Logs (Event ID 4625)

---

### 🟢 Week 2 – IOC Extraction

* Detected suspicious processes (PowerShell, Mimikatz)
* Extracted file hash, command line, parent process
* Analyzed phishing email

---

### 🔴 Week 3 – Alert Triage

* Classified alerts (TP / FP / Investigation)
* Correlated alerts with system logs
* Identified malicious behavior

---

### 🔵 Week 4 – Threat Hunting

* Identified attacker IP: 10.10.50.200
* Detected malware: mimikatz.exe
* Extracted PowerShell command
* Created full attack timeline

---

## 🚨 Attack Scenario

Brute Force → Malware Execution → PowerShell Data Exfiltration

---

## 🧠 Key Skills Gained

* Log Analysis using Splunk
* Threat Detection & IOC Analysis
* Alert Triage & Correlation
* Incident Response & Reporting

---

## ✅ Conclusion

This project demonstrates practical SOC analyst skills, including detecting and investigating real-world attack scenarios using log data and SIEM tools.
