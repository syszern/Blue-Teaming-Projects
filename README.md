# 🛡️ 30-Day Defensive Security Projects

A collection of **case files** documenting my 30-Day SOC/Blue Teaming Challenge.  
Each case demonstrates practical skills in **SIEM, log analysis, threat detection, incident response, and automation**.

> All work is hands-on, reproducible, and structured to demonstrate real-world defensive security capabilities.


## 📂 Case File Index  

| Day | Case Title | Status | ATT&CK Ref | Link |
|-----|------------|--------|------------|------|
| 1   | Windows Event Log Analysis (Failed Logons) | 🔄 In Progress | T1078, T1110 | [Case01](./Week1_LabSetup/Day1_WindowsVM) |
| 2   | Linux Auth Log Analysis (SSH Brute Force) | ⬜ Not Started | T1110, T1078 | [Case02](./Week1_LabSetup/Day2_LinuxVM) |
| 3   | Network Log Analysis (Port Scanning) | ⬜ Not Started | T1046 | [Case03](./Week1_LabSetup/Day3_KaliVM) |
| 4   | Splunk Rule Creation (Suspicious PowerShell) | ⬜ Not Started | T1059.001, T1086 | [Case04](./Week1_LabSetup/Day4_SplunkInputs) |
| 5   | Suricata IDS Alert Review (Malicious Traffic) | ⬜ Not Started | T1040, T1071 | [Case05](./Week1_LabSetup/Day5_WindowsLogs) |
| 6   | Brute Force Detection Playbook | ⬜ Not Started | T1110 | [Case06](./Week1_LabSetup/Day6_LinuxLogs) |
| 7   | Phishing Incident Response Playbook | ⬜ Not Started | T1566, T1059 | [Case07](./Week1_LabSetup/Day7_LabDocs) |
| 8   | Malware Execution Containment Playbook (Blue-Focused) | ⬜ Not Started | T1059, T1204 | [Case08](./Week2_AlertTriage/Day8_MITREMapping) |
| 9   | Insider Threat Scenario (File Access & Data Removal) | ⬜ Not Started | T1078, T1531 | [Case09](./Week2_AlertTriage/Day9_FailedLogins) |
| 10  | Threat Hunting: Persistence via Registry & Scheduled Tasks | ⬜ Not Started | T1060, T1547 | [Case10](./Week2_AlertTriage/Day10_SuspiciousPowerShell) |
| 11  | Threat Hunting: Credential Dumping Detection | ⬜ Not Started | T1003 | [Case11](./Week2_AlertTriage/Day11_NetworkTraffic) |
| 12  | Threat Hunting: Lateral Movement Detection | ⬜ Not Started | T1021, T1075 | [Case12](./Week2_AlertTriage/Day12_AlertClassification) |
| 13  | Threat Hunting: Data Exfiltration (Network & DNS) | ⬜ Not Started | T1041, T1071, T1048.003 | [Case13](./Week2_AlertTriage/Day13_MappingVerification) |
| 14  | Access Control Review & Privilege Escalation Paths | ⬜ Not Started | T1078, T1548 | [Case14](./Week2_AlertTriage/Day14_AlertTriageCase) |
| 15  | Vulnerability Assessment & Patch Simulation (Detection Lens) | ⬜ Not Started | T1190, T1068 | [Case15](./Week3_IncidentResponse/Day15_Persistence) |
| 16  | Threat Modeling with PASTA | ⬜ Not Started | T1078, T1566, T1190 | [Case16](./Week3_IncidentResponse/Day16_PersistenceDetection) |
| 17  | Incident Simulation: Ransomware Behavior (Detection-first) | ⬜ Not Started | T1486, T1489 | [Case17](./Week3_IncidentResponse/Day17_LateralMovement) |
| 18  | Incident Simulation: SQL Injection Detection & Remediation | ⬜ Not Started | T1190, T1505 | [Case18](./Week3_IncidentResponse/Day18_LateralDetection) |
| 19  | MITRE ATT&CK Mapping (Real Attack Sample) | ⬜ Not Started | Multiple | [Case19](./Week3_IncidentResponse/Day19_Exfiltration) |
| 20  | Dashboard Building in Splunk (SOC Use Case) | ⬜ Not Started | T1071, T1041 | [Case20](./Week3_IncidentResponse/Day20_ExfiltrationTimeline) |
| 21  | Log Correlation Rules (Multi-source) | ⬜ Not Started | T1078, T1059, T1041 | [Case21](./Week3_IncidentResponse/Day21_IRWorkflow) |
| 22  | Host Forensics: Memory Dump Analysis (Volatility) | ⬜ Not Started | T1003, T1055 | [Case22](./Week4_Automation_Playbooks/Day22_ThreatIntel) |
| 23  | Host Forensics: Disk Artifact Analysis (Autopsy) | ⬜ Not Started | T1070, T1485 | [Case23](./Week4_Automation_Playbooks/Day23_Playbook) |
| 24  | Log Parsing Automation Scripts | ⬜ Not Started | N/A | [Case24](./Week4_Automation_Playbooks/Day24_LogParsingScripts) |
| 25  | Red-Team Simulation: Credential Access (Blue-validated) | ⬜ Not Started | T1110, T1555 | [Case25](./Week4_Automation_Playbooks/Day25_Dashboards) |
| 26  | Red-Team Simulation: Privilege Escalation (Detection Focus) | ⬜ Not Started | T1068, T1548 | [Case26](./Week4_Automation_Playbooks/Day26_AttackSimulation) |
| 27  | Red-Team Simulation: Persistence (Detection & Cleanup) | ⬜ Not Started | T1050, T1547 | [Case27](./Week4_Automation_Playbooks/Day27_IncidentReport) |
| 28  | Threat Intel Integration & Alert Enrichment | ⬜ Not Started | T1071, T1086, T1041 | [Case28](./Week4_Automation_Playbooks/Day28_ThreatIntel) |
| 29  | Windows Firewall Evasion Detection (Proxying / Port Hopping) | ⬜ Not Started | T1562.004, T1071 | [Case29](./Week4_Automation_Playbooks/Day29_InsiderInvestigation) |
| 30  | Data Exfiltration via DNS Tunneling Detection | ⬜ Not Started | T1048.003, T1071.004 | [Case30](./Week4_Automation_Playbooks/Day30_RedBlueEngagement) |

**LEGEND:** ✅ Completed | 🔄 In Progress | ⬜ Not Started  


## 🔹 Key Deliverables

1. **Log Collection and Analysis** – Multi-VM environment with Windows/Linux log forwarding.
2. **Alert Triage & Detection** – Generated and classified alerts, MITRE ATT&CK mapping.
3. **Incident Response & Threat Hunting** – Timeline creation, attack simulation, response workflow.
4. **Automation & Playbooks** – Log parsing scripts, dashboards, threat intelligence integration.


## 🔹 Skills Demonstrated

- Log Analysis (Windows, Linux, and Network telemetry)
- SIEM Administration (Splunk Enterprise / Forwarder)
- Detection Engineering and Rule Tuning
- Threat Hunting and Correlation Logic
- Incident Response and Playbook Development
- Basic Automation using Python/Bash
- Threat Modeling using PASTA Framework
- Red vs Blue Validation (Controlled Simulations)
  

## 🔹 References & Tools
References and tools used throughout the challenge:  

- [Splunk Enterprise](https://www.splunk.com/)
- [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/)
- [Python 3](https://www.python.org/) / Bash scripting
- [MITRE ATT&CK](https://attack.mitre.org/)
- [MISP Threat Intelligence Feeds](https://www.misp-project.org/)
- [AlienVault OTX](https://otx.alienvault.com/)


See full list in [resources.md](resources.md).  


## 🔹 Notes

- All VM snapshots and configurations are documented for reproducibility.
- Splunk dashboards and queries are export-ready for demonstration.
- MITRE ATT&CK mappings included for every detection scenario.



