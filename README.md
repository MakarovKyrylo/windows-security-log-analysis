# windows-security-log-analysis
Investigation of Windows Security Event Logs for threat detection
# Windows Security Log Analysis

This project demonstrates investigation of Windows Security Event Logs to identify suspicious activity.

## Event IDs analyzed

4624 — Successful logon  
4625 — Failed logon  
4688 — Process creation  

## Investigation

I analyzed Windows Security Logs to detect brute-force login attempts and suspicious process execution.

Indicators investigated:
- multiple failed logon attempts
- unusual login times
- abnormal process chains

Example suspicious chain:

winword.exe → cmd.exe → powershell.exe

## Tools used

- Windows Event Viewer
- auditpol
- netstat
- PowerShell

## Goal

Practice threat detection techniques used in Security Operations Centers (SOC).
