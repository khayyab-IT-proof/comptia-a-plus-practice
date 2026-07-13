Weekly Study & Practical Log

---

## 📅 09 July 2026
### 🖥️ System Information (`msinfo32`)
- Checked OS version, system type, CPU, RAM, BIOS/UEFI mode, storage type
- Verified this is a 64-bit Windows 11 system running in UEFI mode

### 🌐 Networking (`ipconfig /all`)
- Identified IPv4 address, subnet mask, default gateway, DNS servers
- Confirmed DHCP is enabled, MAC address for Wi-Fi adapter, lease times
- Matches CompTIA A+ Domain 2 networking objectives

### ⚙️ Device Manager
- Confirmed installed hardware: CPU, SSD drive, Wi-Fi adapter, peripherals
- Checked no devices have errors/warning icons
- Reviewed driver listings and hardware categories
Add daily study & practical log - 09 July 2026

📅 11 July 2026
- **Network tests**: Used ping (connectivity), tracert (route), nslookup (DNS resolution)
- **Disk Management**: Viewed partitions, drive letters, file systems, and free space

📅 13 July 2026
- **Windows Security**: Reviewed firewall, real-time protection, and update settings
- **Event Viewer**: Checked system logs to identify errors/warnings (core troubleshooting skill)
- **Task Manager**: Monitored resource usage, startup items, and running services

13 July 2026 — Extra Tasks
- **User Accounts**: Reviewed admin vs standard privileges, UAC and access control basics
- **MSConfig**: Checked boot configuration, services, and startup control
- **Netstat**: Viewed active network connections and listening ports — core security/troubleshooting

  13 July 2026 — Virtualisation & Recovery Tools
- **Virtualisation / WSL**: Enabled Virtual Machine Platform and Windows Subsystem for Linux (WSL) in Windows Features. Set WSL 2 as default version. Demonstrated understanding of virtualisation concepts, a key CompTIA A+ Core 1 objective.
- **System Restore**: Opened `rstrui.exe` recovery tool. Noted system protection is disabled; explained purpose: rolls back system files/settings to fix issues without deleting personal data.
- **Registry Editor**: Launched `regedit` to safely view Windows configuration database. Recognised main hives (`HKLM`, `HKCU`, etc.) and confirmed no modifications were made.
- **Resource Monitor**: Opened advanced system monitor to view real‑time CPU, memory, disk, and network usage for deep troubleshooting.

  📅 13 July 2026 — Full Session
- **Virtualisation**: Enabled Virtual Machine Platform and Windows Subsystem for Linux (WSL); set WSL 2 as default. Understood virtualisation concepts for running multiple OS environments.
- **System Restore**: Opened `rstrui.exe` recovery tool; noted system protection was off, explained its purpose for rolling back system changes.
- **Registry Editor**: Safely viewed `regedit` and its main hives (`HKLM`, `HKCU`, etc.) — no edits made.
- **Resource Monitor**: Used to check real‑time CPU, memory, disk, and network activity.
- **CHKDSK**: Ran `chkdsk C:` — learned "Access denied" is normal for active system drive; scan scheduled for next boot.
- **Diskpart**: Command‑line tool to list disks, volumes, partitions, and drive letters.
- **SFC /scannow**: Run as Administrator; scan completed successfully — no system file corruption found.
- **IP Reset**: Used `ipconfig /release`, `/renew`, `/flushdns` to refresh network configuration.
