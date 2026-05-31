# Microsoft-Sentinel-Defender-for-Threat-Detection-
How I Built, Attacked, and Defended My Own SOC Using Microsoft Sentinel and Investigated 11 Live Incident.


# Enterprise SOC Simulation: Microsoft Sentinel 
+ Defender Threat Detection Platform

## Overview
A fully functional SOC lab built on Microsoft Azure demonstrating end-to-end threat detection, incident 
response, and threat hunting using Microsoft Sentinel, Microsoft Defender, Sysmon, KQL, and Atomic Red Team.

## Architecture
!(Screenshots/SOC%20Architecture .png)
- 3 Azure VMs (Windows Server 2025 Datacenter x64, Windows 11 Pro, Ubuntu 22.04)
- Microsoft Sentinel SIEM
- Log Analytics Workspace
- Network Security Group with restricted access
- Sysmon v15.20 with SwiftOnSecurity config

## What Was Built
- Custom analytics rules mapped to MITRE ATT&CK
- Data Collection Rules for Windows and Linux endpoints
- KQL threat hunting queries
- Atomic Red Team adversary simulations
- NIST 800-61 incident response documentation

## Techniques Simulated
| Technique | ID | Tool |
|-----------|-----|------|
| PowerShell Execution | T1059.001 | Atomic Red Team |
| Registry Run Key | T1547.001 | Atomic Red Team |
| Brute Force | T1110.001 | Atomic Red Team |
| Credential Dumping | T1003 | Mimikatz via ART |

## Results
- 11 high-severity incidents generated
- End-to-end detection validated in under 30 minutes
- Full incident response documented using NIST 800-61

## Tools Used
Microsoft Azure | Microsoft Sentinel | Defender XDR | 
Sysmon | KQL | Atomic Red Team | MITRE ATT&CK | NIST 800-61

## Documentation
- Incident Response Report Following the NIST 800-61
- Project process documentation via Substack and Personal Portfolio ( You should check that out)

