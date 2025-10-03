# Working with the File System – Hands-On Lab

## Overview
This lab reinforced Linux command-line skills by practicing file system operations.  
I connected to an Amazon Linux EC2 instance and learned how to:
- Create folders and files
- Copy and move files/directories
- Delete and reorganize files/directories
- Validate folder structures using `ls -laR`



## Steps Completed
1. **Connected to the EC2 instance** using PuTTY and the `.ppk` key file.  
2. **Created the CompanyA directory** with three subfolders: `Finance`, `HR`, and `Management`.  
3. **Created CSV files** within each subfolder using the `touch` command.  
4. **Verified file system structure** with `ls` and `ls -laR`.  
5. **Reorganized the structure**:
   - Copied `Finance` into the `HR` folder.  
   - Moved `Management` under the `HR` folder.  
   - Created an `Employees` folder inside `HR` and moved files there.  
6. **Validated final structure** with recursive listing.


## Screenshots
PuTTY SSH session (successful login)

<img width="664" height="412" alt="Screenshot 2025-10-03 065448" src="https://github.com/user-attachments/assets/b0128efa-4d3f-4710-a27d-63f129eb5659" />

Terminal after creating **CompanyA** and subdirectories.  
<img width="757" height="557" alt="Screenshot 2025-10-03 070854" src="https://github.com/user-attachments/assets/60bb3093-1360-467e-9e80-dc953cfec354" />

Terminal showing files created inside Finance, HR, and Management.
 <img width="617" height="538" alt="Screenshot 2025-10-03 070956" src="https://github.com/user-attachments/assets/2728b704-e177-44c2-9faa-aa130b1952cc" />
 
 `ls -laR` output after reorganization (showing final structure).
 <img width="799" height="694" alt="Screenshot 2025-10-03 071649" src="https://github.com/user-attachments/assets/1a27412c-bb25-4171-9b81-5ed750e66756" />

## AWS Architecture Diagram

<img width="1024" height="1024" alt="BCO bbe1e0b3-1b3d-42ae-b430-63ba3c483178" src="https://github.com/user-attachments/assets/691a55ae-b8be-4f9d-9698-151aedca1603" />


## What I Learned

How to create and manage directories in Linux using mkdir, touch, and ls.

The difference between rm -r and rmdir.

How to use relative paths (../) and absolute paths effectively.

Best practices for reorganizing file systems.



## Final Folder Structure
The final directory layout of **CompanyA** after reorganization 
```plaintext
CompanyA/
└── HR/
    ├── Employees/
    │   ├── Assessments.csv
    │   └── TrialPeriod.csv
    ├── Finance/
    │   ├── ProfitAndLossStatements.csv
    │   └── Salary.csv
    └── Management/
        ├── Managers.csv
        └── Schedule.csv

