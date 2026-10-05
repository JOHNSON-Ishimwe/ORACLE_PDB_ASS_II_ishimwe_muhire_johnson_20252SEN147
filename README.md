# Oracle 21c Pluggable Database Management

## Overview of Tasks
This repository contains the required execution evidence for creating, managing, and deleting Pluggable Databases ( and user in Oracle 21c, as well as verifying the setup via Oracle Enterprise Manager (OEM)

## Oracle Environment Used
* **Database:** Oracle Database 21c
* **OS:** Windows 10 hp
* **Tools:** SQLPlus / Oracle Enterprise Manager (OEM)

## Explanation of Each Task
1. **Task 1:**  created the pluggable database `is_pdb_20252SEN147`, opened it, and provisioned the user `ishimwe_20252SEN147` with DBA privileges.
2. **Task 2:** Created a temporary database `is_to_delete_pdb_20252SEN147`, verified its existence in `show pdbs`, and successfully executed a complete drop including datafiles.
3. **Task 3:** Accessed the OEM Express dashboard to visually verify the active container environment.
4. **Task 4:** Structured the documentation and screenshot evidence in a public GitHub repository.

## Challenges 
*  Ensuring the temporary PDB was closed before executing the DROP command. Resolved by verifying the open_mode in show pdbs

## Submission Detai
* **PDB Name Created:** is_pdb_20252SEN147
* **Issues Encountered:** just cmd promt miss typing and  creating pdb using path folder but solved<img width="2560" height="1440" alt="Screenshot_(151)" src="https://github.com/user-attachments/assets/86a0c223-141c-46a9-a7da-84a9a7fae678" />
<img width="2560" height="1440" alt="Screenshot_(149)" src="https://github.com/user-attachments/assets/b4c44c34-2063-4098-8ffc-b1556a6ccd47" />
<img width="2560" height="1440" alt="Screenshot_(147)" src="https://github.com/user-attachments/assets/33875937-6ff0-465f-8444-89b5d48eb6dd" />
<img width="2560" height="1440" alt="Screenshot_(146)" src="https://github.com/user-attachments/assets/ea2a96c9-9e74-4ff5-9e2a-46410cc93db7" />
<img width="1237" height="613" alt="em" src="https://github.com/user-attachments/assets/1d4fee30-b669-4d44-8387-abf847a7bd28" />
