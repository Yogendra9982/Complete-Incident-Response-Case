# 🧾 Complete Incident Response Case

**End-to-End Incident Response Investigation using Windows Logs, Sysmon & Splunk**

---

## 📖 Overview

This project demonstrates a complete Incident Response investigation in a home lab environment. The objective was to detect suspicious activity, investigate the incident, collect evidence, identify Indicators of Compromise (IOCs), build an attack timeline, analyze the root cause, and document the complete investigation.

The investigation follows a practical Incident Response workflow similar to what SOC and DFIR teams perform during real security incidents.

---

## 🎯 Objectives

- Detect suspicious activities
- Investigate Windows and Sysmon logs
- Identify Indicators of Compromise (IOCs)
- Create an attack timeline
- Perform root cause analysis
- Assess the impact of the incident
- Recommend containment actions
- Document the complete investigation

---

## 🧱 Lab Environment

- Kali Linux
- Windows 10
- Splunk Enterprise
- Sysmon
- Windows Event Logs

---

## 📂 Folder Structure

```text
Complete-Incident-Response-Case/
│
├── README.md
├── Reports/
└── Queries/
```

---

## 🧩 Project Workflow

**Phase 1 – Attack Investigation**

*Initial Detection*
Started the investigation by reviewing security logs in Splunk to spot suspicious process execution and unusual system activity.

*IOC Collection*
Collected multiple Indicators of Compromise, including:
- Suspicious processes
- Command lines
- IP addresses
- File names
- File hashes
- Network connections

*Timeline Analysis*
Built a chronological timeline to understand the sequence of attacker actions from initial execution to final activity.

**Phase 2 – Incident Report**

*Root Cause Analysis*
Identified how the malicious activity started and determined the most likely cause of the incident.

*Impact Analysis*
Evaluated the potential impact on the system, including possible credential theft, malware execution, and unauthorized system changes.

*Containment*
Recommended actions included:
- Isolating the affected system
- Terminating malicious processes
- Removing malicious files
- Blocking malicious IP addresses
- Resetting compromised credentials

*Documentation*
Documented the complete investigation with evidence, findings, screenshots, and recommendations.

---

## 🔄 Investigation Process

1. Detect suspicious activity
2. Analyze Windows logs
3. Investigate Sysmon events
4. Collect IOCs
5. Build attack timeline
6. Perform root cause analysis
7. Assess impact
8. Recommend containment
9. Document the incident

---

## 🧠 Skills Demonstrated

Incident Response, Security Monitoring, Log Analysis, Splunk Investigation, Windows Event Analysis, Sysmon Analysis, IOC Identification, Timeline Analysis, Root Cause Analysis, Incident Documentation, Digital Forensics Fundamentals

---

## 🛠️ Technologies Used

- Splunk Enterprise
- Windows 10
- Kali Linux
- Sysmon
- Windows Event Viewer
- PowerShell
- Command Prompt

---

## 💡 Key Learning

This project provided practical experience in handling a complete security incident from detection to documentation. It improved investigation skills, log analysis techniques, evidence collection, and incident reporting using Windows logs, Sysmon, and Splunk.

---

## 🚀 Future Improvements

- Investigate ransomware scenarios
- Analyze phishing attacks
- Detect persistence techniques
- Add MITRE ATT&CK mapping
- Automate IOC detection using Splunk searches

---

## ✅ Conclusion

This project demonstrates a practical end-to-end Incident Response investigation using a home lab. It covers detection, investigation, IOC collection, timeline creation, root cause analysis, containment planning, and professional documentation — providing hands-on experience with the Incident Response lifecycle.

---
