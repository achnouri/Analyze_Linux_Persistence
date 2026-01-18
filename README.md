# Linux Persistence Toolkit (linper)

## Overview
**Linux Persistence Toolkit (linper)** is a Bash-based security research utility designed for **penetration-testing labs and authorized red-team exercises**.  
It focuses on **enumerating, testing, and cleaning persistence mechanisms** commonly found on Linux systems.

### The tool is primarily aimed at:
- Defensive security testing
- Red-team / blue-team labs
- Post-exploitation research
- Detection engineering validation<br><br>

---

> **Legal & Ethical Notice :**  
> This tool is intended **only for educational purposes and authorized environments**.  

---

## Features
- Enumeration of persistence-capable binaries and services
- Multiple persistence vectors (cron, systemd, shell init files, web roots)
- **Dry-run mode** for safe inspection without system modification
- **Cleanup mode** to remove artifacts created by the tool
- Writable directory discovery for temporary files
- Optional stealth-oriented modifications (for research scenarios)
- Basic defensive control enumeration

---

## Use Cases
- Red-team training labs
- Blue-team detection testing
- Persistence awareness education
- CTF challenge development
- Post-exploitation methodology research

---

## Requirements
- Linux system
- Bash
- Standard GNU utilities (`awk`, `grep`, `find`, `crontab`, etc.)
- Root privileges may be required for some techniques

---

## Usage
```bash
bash linper.sh [options]
```


## Installation
Clone the repository and ensure the script is executable:
```bash
git clone https://github.com/achnouri/Analyze_Linux_Persistence
```

---

<br><br><br>

###### [`@achnouri`](https://github.com/achnouri)

