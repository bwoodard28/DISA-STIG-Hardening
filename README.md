# Windows 11 DISA STIG Hardening Lab

This lab demonstrates applying DISA STIG-aligned controls to a Windows 11 VM and validating compliance using Tenable.

## Process
1. Ran initial Tenable STIG compliance audit (baseline).
2. Applied STIG hardening using community PowerShell script in lab environment.
3. Rebooted VM and reran Tenable STIG audit.

## Results
- Baseline scan: 215 failed STIG checks
- Post-hardening scan: 72 failed STIG checks
- Example improvements:
  - Password length policy enforced (14+ characters)
  - Guest account disabled
  - Defender AV real-time protection enabled
