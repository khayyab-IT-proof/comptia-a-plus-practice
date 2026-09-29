# 🖥️ CompTIA A+ Comprehensive Hands-on Practice Portfolio

A complete, structured archive of my practical labs, operating system configuration, and network troubleshooting workflows aligned with the CompTIA A+ core objectives.

---

## 🌐 1. Network Diagnostics & Command-Line Utilities
*Hands-on application of networking commands to troubleshoot connectivity issues, verify local IP addressing, and check active ports.*

### Verifying IP and Testing Configurations
* **Detailed IP Configuration:** Checking network adapters, MAC addresses, and DHCP/DNS server assignments.
  ![IP Config All](./Networking/2026-07-09_ipconfig-all.png)
* **Releasing & Renewing Leases:** Simulating DHCP troubleshooting by clearing and requesting fresh IP addresses.
  ![Release and Renew](./Networking/2026-07-13_cmd_ipconfig_release_renew.png)
* **Flushing DNS Cache:** Resolving local name resolution issues by clearing the resolver cache.
  ![Flush DNS](./Networking/2026-07-13_cmd_ipconfig_flushdns.png)

### Connectivity and Active Port Tracking
* **Network Paths & Ping Diagnostics:** Testing end-to-end latency and verifying host reachability.
  ![Network Tests 1](./Networking/2026-07-11_cmd_network-tests%201.png)
  ![Network Tests 2](./Networking/2026-07-11_cmd_network-tests%202.png)
* **Checking Active Connections:** Monitoring open network ports and routing tables via the command line.
  ![Netstat Ports](./Networking/2026-07-13_cmd_netstat-ports.png)

---

## 🛠️ 2. Core System Maintenance & File System Repair
*Using built-in Windows diagnostic tools to check operating system health, repair system files, and manage volumes.*

### System File Verification & Checking Access
* **System File Checker (`sfc /scannow`):** Verifying operating system file integrity to repair corrupted files.
  ![SFC Scannow](./System-Maintenance/2026-07-13_cmd_sfc_scannow_complete.png)
* **Access Denied / Permissions Check:** Troubleshooting command line errors and elevated privilege restrictions.
  ![Chkdsk Access Denied](./System-Maintenance/2026-07-13_cmd_chkdsk_access_denied.png)

### Storage & Volume Management
* **Disk Management Console:** Partitioning storage, shrinking volumes, and assigning drive letters.
  ![Disk Management Overview](./System-Maintenance/2026-07-11_diskmgmt_overview.png)
* **Diskpart Utility:** Managing drive volumes via command line tools.
  ![Diskpart Volumes](./System-Maintenance/2026-07-13_cmd_diskpart_volumes.png)
* **Drive Properties:** Verifying storage allocation and checking the NTFS file system status.
  ![Drive Properties](./System-Maintenance/2026-07-13_drive-c-properties-ntfs.png)
* **System Information Utility:** Reviewing hardware configurations and native environment states.
  ![System Info](./System-Maintenance/msinfo32.png)

---

## 🔑 3. Identity, Access, & Advanced Security Management
*Configuring explicit local user profiles, verifying folder-level permissions, and system auditing.*

### User Account Administration
* **Advanced User Configuration (`netplwiz`):** Customizing user access control, group memberships, and local account permissions.
  ![Netplwiz Main](./Diagnostics-And-Security/2026-07-13_netplwiz_users-main.png)
* **Advanced Profile Attributes:** Managing secure sign-in settings and properties.
  ![Netplwiz Advanced](./Diagnostics-And-Security/2026-07-13_netplwiz_advanced-tab.png)

### System Permissions & Security Policies
* **Folder Permissions & ACLs:** Reviewing inherited rights, share settings, and access control lists.
  ![Folder Permissions](./Diagnostics-And-Security/2026-07-13_folder-permissions-view.png)
* **Windows Security & Feature Management:** Auditing active host-based firewalls and antivirus protections.
  ![Windows Security Main](./Diagnostics-And-Security/2026-07-13_windows-security.png)
  ![Windows Security Settings](./Diagnostics-And-Security/2026-07-13_windows-security%202.png)

---

## 📊 4. Performance Monitoring & Administrative Consoles
*Tracking active resource utilization, managing startup applications, and verifying system hardware profiles.*

### Performance & Event Logs
* **Task Manager Diagnostics:** Analyzing CPU, RAM, and disk utilization graphs under load.
  ![Task Manager Performance](./Diagnostics-And-Security/2026-07-13_task-manager-performance.png)
* **Resource Monitor:** Deep-diving into active processes, network usage, and memory allocation.
  ![Resource Monitor](./Diagnostics-And-Security/2026-07-13_resource_monitor.png)
* **Event Viewer Logs:** Checking Windows System and Application logs to trace error codes and boot issues.
  ![Event Viewer](./Diagnostics-And-Security/2026-07-13_event-viewer-system.png)

### Advanced Configuration Utilities
* **System Configuration (`msconfig`):** Adjusting boot options, service initializations, and startup programs.
  ![MSConfig Boot Settings](./System-Maintenance/2026-07-13_msconfig_boot-settings.png)
* **Device Manager:** Troubleshooting system peripheral conflicts, driver updates, and unrecognized hardware.
  ![Device Manager](./System-Maintenance/2026-07-09_devicemanager_hardware.png)
* **Registry Editor (`regedit`):** Navigating the Windows hive structure to understand system configuration data.
  ![Registry View](./Diagnostics-And-Security/2026-07-13_registry_view.png)
* **Power Options:** Tweaking power profiles for efficiency and performance tuning.
  ![Power Options](./System-Maintenance/2026-07-13_power_options_plans.png)
* **System Restore Configuration:** Monitoring recovery points and backup allocations.
  ![System Restore Status](./System-Maintenance/2026-07-13_system_restore_disabled.png)

---

## 🧪 5. Advanced Environment Setups
*Exploring virtualization and multi-OS environments.*

* **Windows Subsystem for Linux (WSL):** Attempting native Linux kernel integration on a Windows host.
  ![WSL Setup Attempt](./Labs-And-Virtualization/2026-07-13_wsl_setup_attempt.png)
* **Windows Features Virtualization:** Enabling hypervisor components (`Hyper-V` / Virtual Machine Platform) at the OS level.
  ![Windows Features Virtualization](./Labs-And-Virtualization/2026-07-13_windows_features_virt_enabled.png)
* **Windows Update Logs:** Verifying the machine is patched against recent vulnerabilities.
  ![Windows Update](./Labs-And-Virtualization/2026-07-13_windows-update.png)
