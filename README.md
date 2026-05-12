# SOC-Investigation-Case-Study-using-Splunk

![alt text](Images/splunk-banner.png "Splunk SOC Investigation")

This repository contains my SOC investigation write-ups using 
Splunk Enterprise and the Boss of the SOC (BOTS) dataset.

The investigations focus on:

- Log Analysis
- Incident Investigation
- Brute Force Detection
- Malware Activity
- PowerShell Analysis
- Web Attack Detection
- Authentication Monitoring

All investigations were performed using realistic attack logs from the BOTS dataset inside Splunk.

---

## About Boss of the SOC (BOTS)

Boss of the SOC (BOTS) is a realistic cybersecurity dataset created for SOC analysts and threat hunters.

The dataset contains:

- Windows Event Logs
- Linux Logs
- DNS Logs
- Web Traffic
- Malware Activity
- Authentication Events
- Simulated Cyber Attacks

This project demonstrates practical SIEM investigation workflows using SPL queries and log analysis techniques.

---

## Tools Used

- Splunk Enterprise
- SPL (Search Processing Language)
- BOTS Dataset
- Windows Event Logs
- MITRE ATT&CK Framework

---

## Investigation Write-ups Table

| Investigation | Description |
|:---:|:---:|
| [Firewall Monitoring](Firewall-Monitoring/README.md) | Monitoring firewall logs to identify blocked connections, suspicious source IPs, unusual traffic patterns, and potential network attacks. |

---

## Investigation Methodology

The investigations generally follow these steps:

1. Alert Detection
2. Log Analysis
3. IOC Identification
4. Timeline Creation
5. Threat Hunting
6. MITRE ATT&CK Mapping
7. Analyst Conclusion
8. Recommendations

---

## MITRE ATT&CK Techniques Covered

| Technique ID | Description |
|---|---|
| T1046 | Network Service Discovery |


---






This project was created for educational and defensive cybersecurity purposes only.

All investigations were performed in a controlled lab environment using publicly available training datasets.
