# Lab 02 – User Creation & Group Permissions (Linux)

## Objective
Demonstrate the ability to create and manage Linux users and groups, assign permissions to directories, and enforce least-privilege access. This lab simulates common IT Support tasks related to user onboarding, access control, and permissions management.

---

## Tools Used
- Kali Linux (Virtual Machine)
- Bash Terminal
- Administrative (sudo) privileges

---

## Scenario
An IT Support technician is tasked with onboarding new team members for a security operations team. Users must be created, assigned to a group, and granted access to a shared directory while preventing unauthorized access from other users.

---

## Tasks Performed

### 1. Created New Users
- Created local user accounts for new team members.
- Assigned secure passwords to each account.

### 2. Created a Security Group
- Created a group to represent the SOC team.
- Verified group creation.

### 3. Added Users to the Group
- Added users to the SOC group.
- Confirmed group membership for each user.

### 4. Created a Secure Directory
- Created a shared directory for SOC reports.
- Assigned group ownership to the SOC team.

### 5. Configured Permissions
- Set directory permissions to allow full access for group members.
- Restricted access for all other users.

### 6. Verified Access Control
- Tested file creation as an authorized user.
- Confirmed access denial for unauthorized users.

---

## Commands Used (Examples)
```bash
sudo useradd analyst1
sudo useradd analyst2
sudo passwd analyst1
sudo passwd analyst2

sudo groupadd soc_team
sudo usermod -aG soc_team analyst1
sudo usermod -aG soc_team analyst2

sudo mkdir /soc_reports
sudo chown :soc_team /soc_reports
sudo chmod 770 /soc_reports

