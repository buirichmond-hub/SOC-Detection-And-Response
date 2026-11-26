
# SOC Detection & Response Project

## Project Overview

This project demonstrates a hands-on SOC investigation using Splunk Enterprise to analyze simulated security events, identify suspicious activities, correlate multiple log sources, and map observed behaviors to the MITRE ATT&CK framework.

## Tools and Technologies

- Splunk Enterprise
- Search Processing Language (SPL)
- Windows Security and System Logs
- Sysmon
- Snort IDS
- Python
- MITRE ATT&CK

## Investigation Objectives

- Identify suspicious authentication activity.
- Correlate failed and successful login attempts.
- Investigate suspicious Windows service installations.
- Analyze encoded PowerShell commands.
- Correlate network and endpoint security events.
- Determine incident scope and severity.
- Develop incident response recommendations.

## Key Findings

- Analyzed 169 simulated security events.
- Identified nine failed login attempts followed by a successful login from the same source IP.
- Investigated a suspicious Windows service configured to run as LocalSystem.
- Decoded a Base64-encoded PowerShell command and determined that its content was benign.
- Correlated Windows authentication events with Snort IDS alerts.
- Identified potential account compromise and persistence activity.

## MITRE ATT&CK Mapping

| Technique | Description | Assessment |
|---|---|---|
| T1110.001 | Password Guessing | Suspected |
| T1543.003 | Windows Service | Suspected persistence |
| T1059.001 | PowerShell | Observed benign command |

## Skills Demonstrated

- SIEM log analysis
- Incident triage and investigation
- SPL querying
- Field normalization
- Cross-source event correlation
- Incident scoping
- MITRE ATT&CK mapping
- Technical documentation

## Full Investigation Report

[View Full Investigation Report (PDF)](./SOC_Investigation_Report.pdf)

## Project Status

- [x] Security log analysis
- [x] Incident investigation
- [x] Cross-source correlation
- [x] MITRE ATT&CK mapping
- [x] Incident investigation report
- [ ] Detection rule development
- [ ] Detection rule testing
- [ ] SOC monitoring dashboard
- [ ] Incident response playbook

## Disclaimer

This project uses synthetic security logs in a controlled lab environment for educational purposes. No production systems were involved.

