# RMF-Compliance-Lab-Portfolio-Zakiya-Moore

Welcome to my cybersecurity lab portfolio focused on Risk Management Framework (RMF) documentation and control implementation. Each lab below demonstrates real-world security analysis aligned with NIST SP 800-53 and supports RMF phases such as implementation, assessment, and monitoring.

📚 Included Labs
🔐 1. IAM Lab (Windows)
Objective: Automate user and group creation, apply folder permissions, and validate identity access.

Key Controls: AC-2 (Account Management)

Tools Used: PowerShell, NTFS, GUI tools

Artifacts: IAM_Users_Configured.png, PowerShell scripts, full lab report

🛡️ 2. System Hardening Lab (Windows & Ubuntu)
Objective: Apply password policies, disable unused services, configure firewalls

Key Controls: CM-6 (Configuration Management), SI-4 (System Monitoring)

OS: Windows 11, Ubuntu 24.04

Artifacts: Screenshot sets, service configs, hardening checklist

📈 3. Threat Detection Lab – Phase 3 (Ubuntu)
Objective: Detect failed logins and sudo misuse using auth.log

Key Controls: AC-7 (Unsuccessful Login Attempts), SI-4 (System Monitoring)

Tools Used: auditd, ausearch, journalctl, grep

Artifacts: auth.log screenshots, grep evidence, full PDF report

🔍 4. Vulnerability Scan Lab – Lynis (Ubuntu)
Objective: Run a vulnerability scan, analyze findings, and document mitigation

Key Controls: RA-5 (Vulnerability Scanning), SI-2 (Flaw Remediation)

Tool: Lynis (CLI-based auditing tool)

Artifacts: Scan outputs, screenshots, adjusted PDF report

🧾 Documentation
File Name	Description
RMF_Workbook_Zakiya.xlsx	Control mapping and tracking workbook
RMF_Workbook_Zakiya.pdf	Printable RMF summary report
Threat_Detection_Phase3_Report.pdf	PDF write-up of simulated auth.log attack lab
Vulnerability_Scan_Lab_Report_Adjusted.pdf	PDF for Lynis vulnerability scan findings

📌 Notes
These labs simulate tasks of a junior SOC analyst or RMF documentation support role in a federal or enterprise environment. All work was conducted in isolated VMs with controlled conditions.

