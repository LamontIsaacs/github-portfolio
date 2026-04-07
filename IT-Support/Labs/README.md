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
- Created local user accounts `analyst1`, `analyst2` using administrative privileges.
- Assigned secure passwords to each account.

### 2. Created a Security Group
- Created a group ('soc_team') to represent the security operations team
- Verified group creation using system commands.

### 3. Added Users to the Group
- Added users to the 'soc_team' group.
- Verified group membership using the 'groups' command.

### 4. Created a Secure Directory
- Created a shared directory '/soc_reports'for team use.
- Assigned group ownership to 'soc_team.

### 5. Configured Permissions
- Applied '770'permissions to restrict access to authorized users only.
- Ensured least- privilege access control.

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

## Key Takeaways

- Learned how to create and manage Linux users and groups.
- Applied least privilege access control using chmod and chown.
- Practiced verifying permissions through real testing.
- Gained hands-on experience with user and access management in a Linux environment.

## Resume Bullet

- Created and managed Linux user accounts and groups, implemented role-based access control, and configured secure directory permissions following least privilege principles.

## Screenshots

### Users Created
![Users Created](screenshots/01-users-created.png)

### Group Membership Verified
![Group](screenshots/04-group-membership-verified.png)

### Permissions Configured
![Permissions](screenshots/06-permissions-configured.png)

### Unauthorized Access Denied
![Denied](screenshots/08-unauthorized-access-denied.png)