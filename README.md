# Working with the File System – AWS Hands-On Lab

## Overview
This lab focused on learning and practicing essential Linux file system commands on an **Amazon Linux EC2 instance**. I connected via SSH (PuTTY) to the instance and created, modified, and reorganized files and directories following a real-world style scenario.


## Objectives
- Create a folder structure
- Create empty files
- Copy and move files and directories
- Delete files and directories

---

## Final Structure
CompanyA/
└── HR/
├── Employees/
│ ├── Assessments.csv
│ └── TrialPeriod.csv
├── Finance/
│ ├── ProfitAndLossStatements.csv
│ └── Salary.csv
└── Management/
├── Managers.csv
└── Schedule.csv
---

## Commands Practiced
- `mkdir` – create directories  
- `touch` – create files  
- `ls`, `pwd`, `ls -laR` – navigate and verify  
- `cp -r` – copy folders  
- `mv` – move files/folders  
- `rm`, `rmdir` – delete files/folders  

---

## Architecture
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/6f4f4228-93b4-4955-96f3-527dc2c7997a" />


---

## Screenshots to Include
- PuTTY SSH session (successful login).  
- Terminal after creating **CompanyA** and subdirectories.  
- Terminal showing files created inside Finance, HR, and Management.  
- `ls -laR` output before reorganization.  
- `ls -laR` output after reorganization (showing final structure).  

---

## What I Learned
- How to navigate the Linux filesystem efficiently.  
- The difference between `rm` (delete files) and `rmdir` (delete empty directories).  
- Using `cp -r` to duplicate directories.  
- How to reorganize a directory tree with `mv`.  
- Gained practical, hands-on Linux administration skills in AWS.
