# ServerAdmin Toolkit (Windows Server 2022)

A menu-driven PowerShell toolkit designed to help system administrators perform common Windows Server tasks quickly, safely, and consistently from a single interface.

This tool was built for learning, lab environments, and portfolio demonstration, following real-world sysadmin workflows.

---

## Features

The toolkit provides fast access to common administrative tasks without manually searching through Windows menus or consoles.

### User and Computer Management
- List local users
- Add and remove local users
- Local password policy checks
- Active Directory user management (if AD module is available)
- Active Directory computer management
- Disable or move computer accounts to OUs

### Network and Security
- View network configuration and active connections
- Scan for open TCP ports
- Zero Trust mode (block all inbound firewall rules with confirmation)
- Allow-list wizard for essential services after Zero Trust
- Firewall rule enable, disable, backup, and restore
- SMB hardening checks (SMBv1, signing, NTLM settings)
- WinRM enable, disable, and TrustedHosts management

### Services and System
- List Windows services using reliable CIM queries
- Search services by name or display name
- Stop and disable unwanted or risky services
- Clear status reporting with verification

### Group Policy
- List all Group Policy Objects
- Search GPOs by name
- View direct and inherited GPO links for an OU or domain
- Save GPO information to logs

### DNS and DHCP
- DNS zone and record checks (if DNS role is installed)
- DHCP scope and lease inspection (if DHCP role is installed)
- Input validation to prevent incorrect commands

### Logging and Reporting
- All actions and outputs are logged
- Logs are saved per session with timestamps
- Easy to export data for reports or audits

---

## How to Run

1. Open **PowerShell as Administrator**
2. Navigate to the project folder:
   ```powershell
   cd D:\Github\serveradmin-toolkit


