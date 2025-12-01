# Linux-Handbook
<!-- ========================= -->
<!--   L I N U X   H A N D B O O K   B A N N E R   -->
<!-- ========================= -->

<p align="center">
  <img src="https://img.icons8.com/?size=200&id=61088&format=png" width="140" alt="Linux Logo"/>
</p>

<h1 align="center">🐧 LINUX-HANDBOOK</h1>

<p align="center">
  <b>Your Complete, Structured, Production-Grade Linux & DevOps Guide</b><br>
  Covers Basics → Intermediate → Advanced Real-World Server Automation
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-blue?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Role-DevOps%20Engineer-green?style=for-the-badge&logo=dev.to"/>
  <img src="https://img.shields.io/badge/Category-System%20Administration-orange?style=for-the-badge&logo=gnu"/>
  <img src="https://img.shields.io/badge/Automation-Shell%20Scripts-yellow?style=for-the-badge&logo=gnubash"/>
</p>

---


---

# 🚀 **Linux Handbook for DevOps Engineers**

A structured, production-ready Linux guide covering **foundational administration**, **daily DevOps automation**, and **advanced enterprise-level system engineering**.

---

# 📁 **Repository Structure**

Organized into **3 professional learning tiers**

---

# 🔵 **LEVEL 1 – BASIC (FOUNDATIONAL LINUX ADMIN)**

Master the essentials every DevOps engineer must know before touching automation or CI/CD.
💡 *Focus: Users, permissions, packages, filesystem*

---

## 👤 **Users & Groups**

* 🧩 **User Creation Script** → [`create_users.sh`](level-1-basic/users/create_users.sh)
* 🔐 **Sudoers Configuration**

  * [`alice-dev`](level-1-basic/users/sudoers/alice-dev)

---

## 📂 **Directory Permissions**

* 📁 **Project Directory Setup** → [`setup_project_dirs.sh`](level-1-basic/permissions/setup_project_dirs.sh)

---

## 📦 **Package Installation**

* 🛠️ Install essential packages (nginx, git, java, etc.)
  → [`install_packages.sh`](level-1-basic/packages/install_packages.sh)

---

---

# 🟧 **LEVEL 2 – INTERMEDIATE (DAILY DEVOPS TASKS)**

Automation, monitoring, logs — the **everyday toolbox** of real-world DevOps.

---

## ⏱️ **Cron Jobs & Automation**

* 🔄 **Application Backup** → [`backup_myapp.sh`](level-2-intermediate/cron/backup_myapp.sh)
* 🧹 **Log Cleanup Automation** → [`cleanup_logs.sh`](level-2-intermediate/cron/cleanup_logs.sh)
* ❤️ **Application Health Check** → [`app_health.sh`](level-2-intermediate/cron/app_health.sh)
* 📘 **Crontab Patterns & Examples** → [`crontab_examples.txt`](level-2-intermediate/cron/crontab_examples.txt)

---

## 📝 **Log Management**

* 📚 **Log Locations, Tips, Troubleshooting Notes**
  → [`log_management_notes.md`](level-2-intermediate/logs/log_management_notes.md)

---

## 📊 **Monitoring & Troubleshooting Commands**

* 👀 CPU, memory, disk, I/O, services, networking
  → [`monitoring_commands.md`](level-2-intermediate/monitoring/monitoring_commands.md)

---

---

# 🔴 **LEVEL 3 – ADVANCED (PRODUCTION-GRADE LINUX)**

Now stepping into **professional DevOps/Platform Engineering** territory — systemd, SSH hardening, LVM, firewalling & log rotation.

---

## ⚙️ **Systemd Services (Production Startup Control)**

* 🧩 **myapp.service (Unit File)**
  → [`myapp.service`](level-3-advanced/systemd/myapp.service)
* ▶️ **Start Script**
  → [`start.sh`](level-3-advanced/systemd/start.sh)

---

## 🔐 **SSH Hardening & Enterprise Security**

* 🔒 **Secure SSH Config Changes**
  → [`sshd_config_changes.txt`](level-3-advanced/ssh-hardening/sshd_config_changes.txt)
* 🔑 **Add Authorized SSH Key Script**
  → [`add_authorized_key.sh`](level-3-advanced/ssh-hardening/add_authorized_key.sh)

---

## 💽 **LVM Storage Management**

* 📦 PV → VG → LV setup + resizing
  → [`lvm_setup_commands.sh`](level-3-advanced/lvm/lvm_setup_commands.sh)

---

## 🔥 **Firewall Rules (UFW & nftables)**

* 🛡️ **UFW Rules** → [`ufw_rules.sh`](level-3-advanced/firewall/ufw_rules.sh)
* 🧱 **nftables Rules** → [`nftables_rules.sh`](level-3-advanced/firewall/nftables_rules.sh)

---

## 📑 **Log Rotation (Production Logging)**

* ♻️ **Daily rotation with compression & retention**
  → [`myapp.logrotate`](level-3-advanced/logrotate/myapp.logrotate)

---

---

# 🧭 **Why This Handbook?**

Designed specifically for **DevOps Engineers**, **SREs**, and **Platform Teams**, this guide helps you:

✔ Build Linux foundations
✔ Automate daily tasks
✔ Operate production workloads
✔ Apply real-world enterprise hardening practices

It’s structured for **training**, **interviews**, **documentation**, and **production onboarding**.

---
# ✍️ **Author**  
### **Attaluri Sai Teja**  

<p align="left">
  <img src="https://img.shields.io/badge/DevOps-Engineer-green?style=for-the-badge&logo=google-cloud&logoColor=white"/>
</p>