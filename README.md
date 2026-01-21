# Linux Automation Scripts 🐧⚙️

A curated collection of **production-ready Linux shell scripts** designed to automate common **system administration, monitoring, backup, networking, and security tasks**.

This repository focuses on:
- Real-world use cases
- Clean and readable Bash scripting
- Defensive scripting & error handling
- Practical automation used in Linux environments

---

## 📂 Repository Structure


---

## 🚀 Scripts Overview

### 🖥 System Scripts
| Script | Description |
|------|------------|
| `cpu_memory_monitor.sh` | Monitors CPU & RAM usage and alerts on threshold |
| `disk_usage_alert.sh` | Sends alert when disk usage exceeds limit |
| `process_watcher.sh` | Restarts critical processes if they stop |

---

### 💾 Backup Scripts
| Script | Description |
|------|------------|
| `directory_backup.sh` | Automated directory backup with rotation |
| `mysql_backup.sh` | MySQL database backup with timestamp |

---

### 🌐 Networking Scripts
| Script | Description |
|------|------------|
| `port_checker.sh` | Checks if a TCP port is open |
| `website_health_check.sh` | Monitors website availability |

---

### 🔐 Security Scripts
| Script | Description |
|------|------------|
| `failed_login_alert.sh` | Alerts on repeated failed SSH login attempts |

---

### 🛠 Utilities
| Script | Description |
|------|------------|
| `log_cleanup.sh` | Cleans old log files safely |

---

## ⚙️ Requirements

- Linux OS
- Bash 4+
- Common Linux utilities (`awk`, `sed`, `grep`, `cron`)

---

## 📌 Usage Example

```bash
chmod +x disk_usage_alert.sh
./disk_usage_alert.sh
