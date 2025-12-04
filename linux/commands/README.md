# 🐧 Linux Commands Cheat Sheet

A simple and quick reference guide for essential Linux terminal commands on **Linux OS** by 
the community-loved open-source project.

---

## 📁 File & Directory
- `ls` → List files
- `ls -a` → Show hidden files
- `ls -l` → Detailed list
- `pwd` → Print working directory
- `cd <dir>` → Change directory
- `cd ..` → Go one directory back
- `mkdir <name>` → Make directory
- `rmdir <name>` → Remove empty directory
- `rm -r <name>` → Delete directory with contents
- `touch <file>` → Create empty file
- `cp <src> <dest>` → Copy file
- `cp -r <src> <dest>` → Copy directory recursively
- `mv <src> <dest>` → Move/Rename file or folder
- `cat <file>` → View file
- `nl <file>` → View file with line numbers
- `head <file>` → View top 10 lines
- `tail <file>` → View last 10 lines
- `tail -f <file>` → Live log view
- `find / -name <file>` → Search file from root

---

## ✏️ Editors
- `vi <file>` → Open in vi editor
- `nano <file>` → Open in nano editor
- `gedit <file>` → Open in GUI editor

---

## 🔐 Permissions & Users
- `whoami` → Current user
- `who` → Logged in users
- `su <user>` → Switch user
- `passwd <user>` → Set password
- `sudo <cmd>` → Run command as admin
- `chmod 777 <file>` → Full permissions
- `chmod 755 <file>` → Owner write, all read+execute
- `chown <user> <file>` → Change ownership

---

## ⚙️ Processes
- `top` / `htop` → Process monitor
- `ps aux` → Show all running processes
- `kill <PID>` → Kill process by ID
- `killall <name>` → Kill process by name
- `systemctl start <service>` → Start service
- `systemctl stop <service>` → Stop service
- `systemctl status <service>` → Check service status

---

## 💾 Disk & Memory
- `df -h` → Disk usage in human readable format
- `du -sh <dir>` → Directory size
- `free -m` → RAM usage

---

## 🌐 Network
- `ip a` / `ifconfig` → Show IP address
- `ping <ip/url>` → Connectivity test
- `ssh <user>@<ip>` → Remote login
- `scp <file> <user>@<ip>:<path>` → Copy to remote server
- `netstat -tulnp` → Show open ports

---

## 📦 Package Managers
- `apt update` → Update packages (Debian/Ubuntu)
- `apt install <pkg>` → Install package
- `yum install <pkg>` → Install package (RHEL)
- `dnf install <pkg>` → Install package (Fedora)
- `rpm -ivh <file.rpm>` → Install .rpm file
- `snap install <pkg>` → Install using snap

---

## 🗒 Logs & System Info
- `journalctl` → View system logs
- `dmesg` → Boot logs
- `uptime` → System uptime
- `date` → Show current date/time
- `uname -r` → Kernel version
- `history` → Command history
- `clear` → Clear terminal
- `man <cmd>` → Command manual/help

---

## 🔄 Git (on Linux)
- `git clone <repo>` → Clone a repository
- `git pull` → Fetch latest changes
- `git status` → Check repo status

---

### ⭐ Tips
✔ Linux terminal is case-sensitive  
✔ Use `sudo` for administrative tasks  
✔ Git tracks files, not folders  

---

Made with 💙 for faster learning 🚀
