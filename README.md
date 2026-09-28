# SOC Level 1 Capstone Investigations

This repository documents my hands-on SOC Level 1 capstone investigations completed through TryHackMe.

The goal of this repository is to demonstrate practical experience in incident response, log analysis, network forensics, memory forensics, phishing analysis, and attack-chain reconstruction.

## Investigations

### [Tempest](./Tempest/)
Windows incident response investigation involving malicious document execution, command-and-control activity, internal reconnaissance, privilege escalation, and persistence.

### [Boogeyman 1](./Boogeyman-1/)
Phishing and network forensics investigation focused on malicious attachments, PowerShell activity, command-and-control traffic, and data exfiltration.

### [Boogeyman 2](./Boogeyman-2/)
Memory forensics investigation involving phishing analysis, VBA macro analysis, malicious process execution, C2 communication, and scheduled task persistence.

### [Boogeyman 3](./Boogeyman-3/)
Elastic-based investigation covering process execution, persistence, C2 activity, UAC bypass, credential access, lateral movement, DCSync, and ransomware deployment.

## Skills Demonstrated

- SOC investigation methodology
- Incident response
- Phishing email analysis
- Windows Event Log analysis
- Sysmon analysis
- PowerShell log analysis
- Elastic / Kibana investigation
- KQL filtering
- Memory forensics with Volatility
- VBA macro analysis
- PCAP and network traffic analysis
- Command-and-control detection
- Process parent-child analysis
- Persistence detection
- Privilege escalation investigation
- Credential access analysis
- Lateral movement detection
- Data exfiltration analysis
- Ransomware activity investigation
- Attack-chain reconstruction

## Tools Used

- Elastic Stack
- Kibana
- Volatility
- Olevba
- Wireshark
- Brim
- Event Viewer
- Sysmon
- Timeline Explorer
- EvtxECmd
- Linux command-line tools

## Attack Investigation Workflow

```text
Alert / Initial Evidence
        ↓
Identify Suspicious Activity
        ↓
Analyse Processes and Logs
        ↓
Investigate Network Activity
        ↓
Identify Persistence / Privilege Escalation
        ↓
Trace Credential Access and Lateral Movement
        ↓
Reconstruct the Full Attack Chain
```
Learning Outcome
These investigations helped me develop a better understanding of how security analysts correlate evidence from multiple sources rather than analysing individual events in isolation.
Working through the incidents strengthened my ability to follow attacker activity from initial compromise through post-exploitation, persistence, lateral movement, and impact.
