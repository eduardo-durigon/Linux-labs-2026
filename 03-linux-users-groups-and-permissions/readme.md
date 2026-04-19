## 🧪 Lab 03 – Linux Users, Groups, and Permissions

### 🎯 Objective

Practice user and group management, ownership, and permission control in Linux while applying the principle of least privilege.

### 🛠️ What I Did

* Created multiple users and a shared group
* Assigned group memberships
* Built a structured directory with different access levels
* Configured ownership using `chown`
* Applied permissions using `chmod`
* Tested access between users to validate restrictions

### 🔐 Key Concepts

* User and group-based access control
* File and directory permissions (`rwx`)
* Ownership and privilege boundaries
* Importance of execute (`x`) permission on directories
* Least privilege principle in practice

### 🧪 Results

* **analyst1** → Full access to all resources
* **employee1** → Limited access (public only)
* Access restrictions successfully enforced and validated

### 📁 Environment

* Ubuntu Server (VM)
* Commands: `useradd`, `groupadd`, `usermod`, `chown`, `chmod`, `su`

### 🧠 Takeaway

This lab reinforced how Linux enforces access control through users, groups, and permissions, and how misconfigurations can directly impact security.
