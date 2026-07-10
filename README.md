<h1 align="center">🐧 Linux Commands</h1>

<p align="center">
Essential Linux Commands with Descriptions & Examples
</p>

<p align="center">

![Linux](https://img.shields.io/badge/Linux-Commands-blue?style=for-the-badge&logo=linux)

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Kali-red?style=for-the-badge)

</p>

---

# 📖 About

This repository contains essential Linux commands with descriptions and examples. It is designed for beginners learning Linux, Cybersecurity, and Ethical Hacking.

---

# 📑 Table of Contents

- System Update
- Navigation & File Management
- User & Permission Management
- Networking Commands
- File Search & Manipulation
- Privilege Escalation & Enumeration
- Security & Penetration Testing Tools

---

# 🔄 System Update

| Command | Description | Example |
|---------|-------------|---------|
| sudo apt update | Updates package list | sudo apt update |
| sudo apt upgrade | Upgrades installed packages | sudo apt upgrade |

---

# 📁 Navigation & File Management

| Command | Description | Example |
|---------|-------------|---------|
| pwd | Displays current directory | pwd |
| ls | Lists files | ls |
| ls -la | Lists all files including hidden | ls -la |
| cd | Change directory | cd /var/www/html |
| cp | Copy files | cp file.txt /tmp/ |
| mv | Move/Rename files | mv old.txt new.txt |
| rm | Remove file | rm file.txt |
| rm -rf | Delete directory | rm -rf test |
| cat | Show file contents | cat /etc/passwd |
| nano | Nano editor | nano config.txt |
| vim | Vim editor | vim config.txt |
| touch | Create empty file | touch hello.txt |
| mkdir | Create directory | mkdir myfolder |

---

# 👤 User & Permission Management

| Command | Description | Example |
|---------|-------------|---------|
| whoami | Show current user | whoami |
| id | Show User ID | id |
| sudo | Execute as root | sudo apt update |
| chmod | Change permissions | chmod 755 script.sh |
| chmod +x | Make executable | chmod +x script.sh |
| passwd | Change password | passwd user |

---

# 🌐 Networking Commands

| Command | Description | Example |
|---------|-------------|---------|
| ping | Test network | ping google.com |
| ifconfig | Network information | ifconfig |
| ip a | Show IP Address | ip a |
| netstat | Network statistics | netstat |
| ss -tuln | Listening ports | ss -tuln |
| nmap | Port scanner | nmap -sV 192.168.1.1 |
| curl | Download webpage | curl http://example.com |
| wget | Download file | wget https://example.com/file.zip |
| traceroute | Trace network path | traceroute google.com |
| dig | DNS lookup | dig example.com |
| nslookup | DNS lookup | nslookup example.com |

---

# 🔍 File Search & Manipulation

| Command | Description | Example |
|---------|-------------|---------|
| find | Find files | find / -name "*.php" |
| grep | Search inside files | grep "admin" config.php |
| locate | Locate file | locate php.ini |
| file | Detect file type | file shell |
| history | Show command history | history |

---

# ⚡ Privilege Escalation & Enumeration

| Command | Description | Example |
|---------|-------------|---------|
| sudo -l | List sudo permissions | sudo -l |
| ps aux | Running processes | ps aux |
| uname -a | Kernel information | uname -a |
| env | Environment variables | env |

---

# 🛡 Security & Penetration Testing Tools

| Command | Description | Example |
|---------|-------------|---------|
| msfconsole | Metasploit Framework | msfconsole |
| hydra | Password brute-force | hydra -l admin -P passwords.txt 192.168.1.5 ssh |
| john | Password cracker | john --wordlist=rockyou.txt hashes.txt |
| nikto | Web vulnerability scanner | nikto -h http://target |
| sqlmap | SQL Injection tool | sqlmap -u "http://site.com?id=1" --dbs |
| burpsuite | Web proxy | burpsuite |
| dirb | Directory brute force | dirb http://target |
| gobuster | Fast directory brute force | gobuster dir -u http://target -w wordlist.txt |
| wireshark | Packet analyzer | wireshark |

---

# ⭐ Author

**M M Ahsan Uddin**

Cybersecurity Enthusias

