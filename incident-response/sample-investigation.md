# Incident Investigation Report (Sample)

## Alert Summary
Suspicious PowerShell execution detected from Windows endpoint.

## Detection Source
SIEM alert – PowerShell encoded command execution.

## Investigation Steps
- Reviewed process tree and user context
- Checked related authentication logs
- Correlated endpoint events with SIEM telemetry
- Validated IOC indicators

## MITRE ATT&CK Mapping
T1059 – Command and Scripting Interpreter

## Containment Actions
- Host isolation (simulated)
- User session validation
- Alert escalation for further review

## Lessons Learned
- Improve PowerShell logging visibility
- Enhance detection tuning for encoded commands
