# 🖥️ Lab 03: Active Directory Domain Setup

## 🎯 Objective

Deploy and configure a Windows Server domain controller using Active Directory Domain Services (AD DS) in a virtualized lab environment.

---

## 🛠️ Technologies Used

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- DNS
- Oracle VirtualBox
- Windows Networking
- Static IP Configuration

---

## 📘 Lab Scenario

An organization requires centralized identity and access management for users and systems. A Windows Server domain controller was deployed and configured to provide Active Directory services, DNS functionality, and domain-based authentication.

---

## 🔧 Tasks Performed

1. Created a Windows Server virtual machine
2. Installed Windows Server 2025
3. Configured administrator credentials
4. Renamed the server to DC01
5. Configured a static IP address
6. Installed Active Directory Domain Services
7. Promoted the server to a Domain Controller
8. Created a new forest (`lab.local`)
9. Configured DNS and Domain Controller options
10. Validated prerequisite checks
11. Successfully deployed and logged into the domain environment

---

# 📸 Screenshots

## 1️⃣ VM Creation (Initial Setup)
![VM Creation](screenshots/01-vm-creation-initial.png)

---

## 2️⃣ VM Creation With ISO Selected
![ISO Selected](screenshots/02-vm-creation-iso-selected.png)

---

## 3️⃣ Windows Server Installation Language Screen
![Language Screen](screenshots/03-server-install-language-screen.png)

---

## 4️⃣ Install Windows Server
![Install Windows Server](screenshots/04-install-windows-server.png)

---

## 5️⃣ Select Windows Server Edition
![Server Edition](screenshots/05-select-server-edition.png)

---

## 6️⃣ Disk Partition Setup
![Disk Partition](screenshots/06-disk-partition-setup.png)

---

## 7️⃣ Installation Ready
![Installation Ready](screenshots/07-installation-ready.png)

---

## 8️⃣ Administrator Password Setup
![Admin Password](screenshots/08-administrator-password-setup.png)

---

## 9️⃣ Server Manager Dashboard
![Server Dashboard](screenshots/09-server-manager-dashboard.png)

---

## 🔟 Rename Server to DC01
![Rename Server](screenshots/10-rename-server-dc01.png)

---

## 1️⃣1️⃣ Static IP Configuration
![Static IP](screenshots/11-static-ip-configuration.png)

---

## 1️⃣2️⃣ Install Active Directory Domain Services
![AD DS Role](screenshots/12-install-ad-ds-role.png)

---

## 1️⃣3️⃣ Promote Server to Domain Controller
![Promote Domain Controller](screenshots/13-promote-domain-controller.png)

---

## 1️⃣4️⃣ Create New Forest (lab.local)
![Create Forest](screenshots/14-create-new-forest-lab-local.png)

---

## 1️⃣5️⃣ Domain Controller Options
![Domain Controller Options](screenshots/15-domain-controller-options.png)

---

## 1️⃣6️⃣ NetBIOS Domain Name
![NetBIOS](screenshots/16-netbios-domain-name.png)

---

## 1️⃣7️⃣ Active Directory Paths
![AD DS Paths](screenshots/17-ad-ds-paths.png)

---

## 1️⃣8️⃣ Review Configuration
![Review Configuration](screenshots/18-review-configuration.png)

---

## 1️⃣9️⃣ Prerequisite Check Passed
![Prerequisite Check](screenshots/19-prerequisite-check-passed.png)

---

## 2️⃣0️⃣ Domain Controller Login
![Domain Login](screenshots/20-domain-controller-login.png)

---

# 💡 Skills Demonstrated

- Active Directory Administration
- Windows Server Deployment
- Domain Controller Configuration
- DNS Configuration
- Virtualization
- Static IP Networking
- Windows Server Management
- Enterprise Identity Management
- IT Infrastructure Administration

---

# 🛠️ Troubleshooting

- Verified static IP configuration before AD DS deployment
- Addressed prerequisite validation checks
- Confirmed DNS functionality during domain setup
- Validated successful domain controller promotion

---

# ✅ Conclusion

This lab demonstrates the deployment and configuration of a functional Active Directory domain environment using Windows Server 2025. The environment simulates foundational enterprise infrastructure used in real-world IT administration and support operations.