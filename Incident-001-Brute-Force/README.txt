# Incident 001 — Brute Force Investigation

A controlled SOC laboratory investigation of repeated failed
Windows network authentication attempts.

## Objective
Detect, triage and investigate repeated authentication failures.

## Environment
- Windows Server / Active Directory
- Kali Linux
- Windows Security Event Logs
- PowerShell
- MITRE ATT&CK

## Detection
Event ID 4625
Same source IP
Same target account
5+ failures within 10 minutes

## Result
6 failed authentication attempts were detected.
No matching successful authentication was observed.

## ATT&CK
T1110.001 — Password Guessing

## Evidence
See the evidence/ directory.

## Disclaimer
This activity was intentionally generated in an isolated lab.