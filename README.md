# threat-hunting-lab-cases
# Threat Hunting Lab Cases

A collection of independent cybersecurity threat-hunting investigations and
log-analysis case studies based on publicly available security datasets and
lab environments.

Each case documents the investigation methodology, evidence analysis,
indicators identified, findings, and defensive detection opportunities.

## Skills Demonstrated

- Threat Hunting
- Windows Log Analysis
- PowerShell Analysis
- IOC Investigation
- Process Correlation
- MITRE ATT&CK
- KQL-Based Detection & Hunting

## Case Studies

### Case 01 – Windows Logon Activity & PowerShell Investigation

Investigation of Windows logon-related activity followed by PowerShell
process execution, encoded commands, command decoding, IOC identification,
and follow-on activity analysis.

**Key investigation steps:**

`Logon → PowerShell → Task ID 106 → Encoded Command → Decode → IOC Search → Findings`

**Dataset:** OTRF Security-Datasets

**Status:** Completed
