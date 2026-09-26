<p align="center">
  <img src="./jenna-frank-welcome-banner.svg" width="100%" alt="Jenna Frank"/>
</p>

<p align="center">
  <em>Cybersecurity Operations by day. Threat hunter by night.</em><br/>
  <em>Builder of honeypots, breaker of assumptions.</em>
</p>

---

<div align="center">

![WGU](https://img.shields.io/badge/WGU_B.S._Cybersecurity-2027-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)
![Intern](https://img.shields.io/badge/Cybersecurity_Intern-Azure_|_GRC-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)
![CompTIA](https://img.shields.io/badge/CompTIA-A+_|_Network+_|_Security+_in_progress-FFD700?style=flat-square&logoColor=white&labelColor=0d1117)

</div>

**WGU Cybersecurity B.S. (2027)** &nbsp;|&nbsp; CompTIA A+, Network+, Security+ *(in progress)*<br/>
Currently: **Cybersecurity Project Manager** - Built Pacific Watch, a SOC on the Log(N) Pacific cyber range. Threat hunting, Sentinel, KQL, MITRE ATT&CK. Hot Pink Huntress 💗

---

## Projects

---

### 🛡️ [Pacific Watch SOC](https://github.com/jennafrank/cyber-range-soc)

[![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/cyber-range-soc)
[![Defender for Endpoint](https://img.shields.io/badge/Defender_for_Endpoint-FF1493?style=flat-square&labelColor=0d1117)](https://github.com/jennafrank/cyber-range-soc)
[![Logic Apps](https://img.shields.io/badge/Logic_Apps-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/cyber-range-soc)
[![Jira](https://img.shields.io/badge/Jira-FF1493?style=flat-square&logo=jira&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/cyber-range-soc)

The advisory-only SOC I built and run on the Log(N) Pacific cyber range, where beginning analysts learn real SOC work. Detections flow through a Sentinel to Logic Apps to Jira pipeline I built, into Tier 1 and Tier 2 queues, with four-shift handoffs and a seven-value disposition taxonomy. About 50 builders and 15 leaders across six teams. Includes case studies, including the 316-case queue flood that became our detection build standard.

**[View Project →](https://github.com/jennafrank/cyber-range-soc)**

---

### 🔬 [Pacific Watch Detection Engineering](https://github.com/jennafrank/pacific-watch-detection-engineering)

[![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/pacific-watch-detection-engineering)
[![KQL](https://img.shields.io/badge/KQL-FF1493?style=flat-square&labelColor=0d1117)](https://github.com/jennafrank/pacific-watch-detection-engineering)
[![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/pacific-watch-detection-engineering)
[![Detection Engineering](https://img.shields.io/badge/Detection_Engineering-FF1493?style=flat-square&labelColor=0d1117)](https://github.com/jennafrank/pacific-watch-detection-engineering)

The Detection Build Card I wrote: the research-to-release standard every Pacific Watch detection follows, with working templates. The worked example grades my own first production rule against it: 65 requirements, 18 met, 25 partially met, 2 not met, 20 not recorded. Every local rule is traced to the thing that broke.

**[View Project →](https://github.com/jennafrank/pacific-watch-detection-engineering)**

---

### 🎣 [INC-2026-87241: Cloud Identity Compromise & BEC](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)

[![Microsoft Sentinel](https://img.shields.io/badge/Microsoft_Sentinel-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)
[![Microsoft 365](https://img.shields.io/badge/Microsoft_365-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)
[![Entra ID](https://img.shields.io/badge/Entra_ID-FF1493?style=flat-square&labelColor=0d1117)](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)
[![KQL](https://img.shields.io/badge/KQL-FF1493?style=flat-square&labelColor=0d1117)](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)

A full investigation of a Microsoft 365 account takeover. The attacker used legacy authentication to bypass Conditional Access, signed in 583 times with MFA satisfied zero times, ran Graph API reconnaissance, exfiltrated files, and sent a fraudulent payment request to the CFO. Persistence came from inbox rules and a Power Automate flow. Includes the timeline and 5 KQL detections.

**[View Project →](https://github.com/jennafrank/INC-2026-87241-EPIC-Investigation)**

---

### 🤖 JADEPUFFER: Agentic Ransomware Hunt

### Hunting an Autonomous AI Attacker in Microsoft Sentinel

One sentence of instruction. Seventeen minutes. Zero humans. I traced an LLM agent from an unauthenticated Langflow RCE (CVE-2025-3248) through credential theft, lateral movement, and a self-repaired exploit to 1,342 encrypted records across 4 hosts. Includes the KQL hunt queries, full MITRE ATT&CK mapping, and the four detection signals that separated the agent from normal noise.

**[View Hunt →](https://github.com/jennafrank/threat-hunt-agentic-ransomware)**
---

### ⚔️ Imperial STIG Strikes Back

[![Windows](https://img.shields.io/badge/Windows-11-FF1493?style=flat-square&logo=windows&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/Windows-11-FF1493?style=flat-square&logo=windows&logoColor=white&labelColor=0d1117) [![PowerShell](https://img.shields.io/badge/PowerShell-FF1493?style=flat-square&logo=powershell&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/PowerShell-FF1493?style=flat-square&logo=powershell&logoColor=white&labelColor=0d1117) [![STIG Compliant](https://img.shields.io/badge/STIG_Compliant-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/STIG_Compliant-FF1493?style=flat-square&logoColor=white&labelColor=0d1117) [![Audit Policy](https://img.shields.io/badge/Audit_Policy-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/Audit_Policy-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)

Comprehensive Windows 11 STIG compliance remediation. 11 HIGH severity findings remediated through tactical PowerShell operations. 100 → 115 STIG items brought into compliance. Imperial Command's security hardening directive, fully executed.

**[View Campaign →](https://github.com/jennafrank/imperial-stig-strikes-back)**

---

### 🍯 Sable Saint-Claire & The Honeypots

![Python](https://img.shields.io/badge/Python-FF1493?style=flat-square&logo=python&logoColor=white&labelColor=0d1117)
![Docker](https://img.shields.io/badge/Docker-FF1493?style=flat-square&logo=docker&logoColor=white&labelColor=0d1117)
![Azure](https://img.shields.io/badge/Azure-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)

A live SSH honeypot disguised as a Solana validator node. 17 Easter eggs. Real-time attack dashboard. Canary tokens. And one very glamorous gotcha moment. Currently collecting threat intelligence data from the open internet.

**[View Project →](https://github.com/jennafrank/the-honeypots)**
---

## ⚔️ Empire Vulnerability Protocol

### Comprehensive Vulnerability Management Lifecycle

Policy governance, vulnerability detection, risk assessment, remediation operations, and verification closure. 81% vulnerability reduction achieved in the first cycle.

**[View Program →](https://github.com/jennafrank/vulnerability-management-empire)**

---

## 🎯 Threat Hunting & Security Operations

### Threat Hunt: Unauthorized TOR Network Access

Parallel threat hunting investigation documenting TOR browser detection via KQL queries, network telemetry analysis, and forensic timeline reconstruction.

**[View Investigation →](https://github.com/jennafrank/threat-hunting-tor-imperial)**

---

### 🏥 Healthcare Enterprise Honeynet

[![Python](https://img.shields.io/badge/Python-FF1493?style=flat-square&logo=python&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/Python-FF1493?style=flat-square&logo=python&logoColor=white&labelColor=0d1117) [![Docker](https://img.shields.io/badge/Docker-FF1493?style=flat-square&logo=docker&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/Docker-FF1493?style=flat-square&logo=docker&logoColor=white&labelColor=0d1117) [![Azure](https://img.shields.io/badge/Azure-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/Azure-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117) [![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)](https://img.shields.io/badge/MITRE_ATT%26CK-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)

Production-grade two-node honeypot (Meridian HR + Cascade Medical EMR). Real-time SOC dashboard, 3,181 synthetic healthcare documents, threat hunting framework, and attacker behavior analysis.

**[View Honeynet →](https://github.com/jennafrank/healthcare-enterprise-honeynet)**

---

### 🖥️ Active Directory Home Lab

![Windows Server](https://img.shields.io/badge/Windows_Server_2019-FF1493?style=flat-square&logo=windows&logoColor=white&labelColor=0d1117)
![PowerShell](https://img.shields.io/badge/PowerShell-FF1493?style=flat-square&logo=powershell&logoColor=white&labelColor=0d1117)
![VirtualBox](https://img.shields.io/badge/VirtualBox-FF1493?style=flat-square&logo=virtualbox&logoColor=white&labelColor=0d1117)
![Active Directory](https://img.shields.io/badge/Active_Directory-FF1493?style=flat-square&logo=microsoft&logoColor=white&labelColor=0d1117)

Built a full enterprise Active Directory environment from scratch. Dual-NIC domain controller, DHCP, NAT routing, DNS, and a PowerShell script that spun up 1,000 users automatically. This is what your corporate IT environment looks like under the hood.

**[View Project →](https://github.com/jennafrank/active_directory_home_lab)**

---

### ⚡ Brute Force SIEM Lab

![Azure](https://img.shields.io/badge/Azure-FF1493?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)
![Sentinel](https://img.shields.io/badge/Sentinel-FF1493?style=flat-square&logo=microsoft&logoColor=white&labelColor=0d1117)
![EventLog](https://img.shields.io/badge/EventLog-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)
![SIEM](https://img.shields.io/badge/SIEM-FF1493?style=flat-square&logoColor=white&labelColor=0d1117)

Simulated brute force attacks and built detection rules in Azure Sentinel. Because knowing how attacks work is the first step to stopping them.

---

## Currently Learning

![Threat Intel](https://img.shields.io/badge/→_Threat_Intelligence_&_Honeypot_Research-FFD700?style=flat-square&labelColor=0d1117)<br/>
![GRC](https://img.shields.io/badge/→_GRC_Frameworks_(NIST,_ISO_27001)-FFD700?style=flat-square&labelColor=0d1117)<br/>
![AZ-500](https://img.shields.io/badge/→_Azure_Security_(AZ--500)-FFD700?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0d1117)<br/>
![Python](https://img.shields.io/badge/→_Python_for_Security_Automation-FFD700?style=flat-square&logo=python&logoColor=white&labelColor=0d1117)

---

## Connect

🌐 &nbsp;[JennaFrank.co](https://www.JennaFrank.co)<br/>
💼 &nbsp;[LinkedIn](https://linkedin.com/in/jenna-frank-4352b12b0)<br/>
📸 &nbsp;[Instagram](https://www.instagram.com/jennacfrank/)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jennafrank&theme=radical&show_icons=true&hide_border=true&bg_color=0d1117&title_color=FF1493&icon_color=FF1493&text_color=ffffff" alt="Jenna's GitHub Stats"/>
</p>

---

<p align="center">
  <em>"The quieter you become, the more you can hear."</em><br/>
  <em>— and the more attacks you can log. 💋</em>
</p>
