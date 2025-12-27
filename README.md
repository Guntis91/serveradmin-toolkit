\# ServerAdmin Toolkit (Windows Server 2022)



Menu-driven PowerShell toolkit for common sysadmin tasks:

\- Network diagnostics + listening ports

\- Local users + local password policy

\- Active Directory users + computers

\- AD password policy + FGPP

\- GPO quick view (GPMC required)

\- DNS management (DNS role/RSAT)

\- DHCP management (DHCP role/RSAT)

\- Firewall management + backup/restore

\- Zero Trust “block all” + allow-list wizard

\- WinRM enable/disable + TrustedHosts

\- SMB hardening checks

\- Quick TCP port scanning

\- Services management (CIM-based)

\- Logs/monitoring + exports

\- Baseline export reports



\## Run

Open PowerShell as Administrator:



```powershell

Set-ExecutionPolicy -Scope Process Bypass -Force

.\\ServerAdmin-Toolkit.ps1

Logs

Logs are saved to:
C:\AdminToolkit\Logs\<timestamp>\

