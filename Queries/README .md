
# KQL Queries

KQL queries used for both scheduled analytics rules in Microsoft Sentinel 
and ad-hoc threat hunting across Windows Security Events and Sysmon telemetry.

## Files

- `failed_logons.kql`: Detects brute force via failed logon aggregation (T1110)
- `sysmon_powershell.kql`: Detects suspicious PowerShell execution flags (T1059.001)
- `registry_persistence.kql`: Detects registry run key persistence writes (T1547.001)
- `rdp_brute_force.kql`: Detects RDP brute force via LogonType 10 (T1110)
- `computers_sending_logs.kql`: Validates endpoint log coverage across all VMs
