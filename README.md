# Windows 11 DISA STIG Hardening Lab

This lab demonstrates applying DISA STIG-aligned controls to a Windows 11 VM and validating compliance using Tenable.

## Process
1. Ran initial Tenable STIG compliance audit (baseline).
2. Applied STIG hardening using community PowerShell script in lab environment.
3. Rebooted VM and reran Tenable STIG audit.

## Results
- [Baseline scan: 140 failed STIG checks](reports/brice_STIG_windows11_2gitp9.pdf) 
- [Post-hardening scan: 143 failed STIG checks](reports/brice_STIG_windows11_jip7he.pdf)

Baseline Tenable STIG audit identified 140 issues. After applying DISA STIG controls, a follow-up scan enumerated 143 checks, reflecting expanded audit coverage and improved security posture. Key improvements included elimination of credential issues (Plugin 110095), enforced RDP NLA requirements, and hardened LSA protection. Results demonstrate successful application of STIG-aligned baseline and validation through Tenable.
