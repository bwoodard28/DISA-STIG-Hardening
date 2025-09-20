# Windows 11 DISA STIG Hardening Lab

This lab demonstrates applying DISA STIG-aligned controls to a Windows 11 VM and validating compliance using Tenable.

## Process
1. Ran initial Tenable STIG compliance audit (baseline).
2. Applied STIG hardening using community PowerShell script in lab environment.
3. Rebooted VM and reran Tenable STIG audit.

## Results
- [Baseline scan: 140 failed STIG checks](https://www.github.com/bwoodard28/DISA-STIG-Hardening/reports/brice_STIG_windows11_2gitp9.pdf) 
- Post-hardening scan: 72 failed STIG checks
- Example improvements:
  - Password length policy enforced (14+ characters)
  - Guest account disabled
  - Defender AV real-time protection enabled
