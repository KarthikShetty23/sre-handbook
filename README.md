# 🐧 Linux & Git Learning Journey

> **Status:** 🟢 Active Learning (Phase 1)
> 
> **Goal:** Building the foundation for Site Reliability Engineering (SRE).

This repository serves as my personal laboratory and documentation hub. Here, I document every Linux command, Git workflow, and Networking concept I master on my journey to becoming a Cloud Engineer.

---

## 🛠️ Tech Stack & Tools
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/Bash_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## 📚 Linux Command Cheat Sheet
*A log of essential commands I use daily in Ubuntu (WSL2).*

| Category | Command | Description |
| :--- | :--- | :--- |
| **Navigation** | `cd ~` | Go to Home directory |
| | `ls -la` | List all files (including hidden) |
| | `pwd` | Print Working Directory |
| **File Mgmt** | `touch file.txt` | Create an empty file |
| | `mkdir folder` | Create a new directory |
| | `rm -rf folder` | Remove directory (Force) |
| **System** | `top` | View active processes |
| | `df -h` | Check disk space usage |

---

## 🐙 Git Workflow
*The SRE standard workflow for version control.*

```bash
# 1. Start a new feature
git checkout -b feature-name

# 2. Save work
git add .
git commit -m "Added new feature"

# 3. Upload to Cloud
git push origin feature-name
