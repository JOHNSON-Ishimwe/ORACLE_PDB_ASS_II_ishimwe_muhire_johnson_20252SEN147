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

## Challenges & 
* *Example: Ensuring the temporary PDB was closed before executing the DROP command. Resolved by verifying the open_mode in v$pdbs.*

## Submission Detai
* **PDB Name Created:** is_pdb_20252SEN147
* **Issues Encountered:** just cmd promt miss typing and  creating pdb using path folder but solved
![alt text](Screenshot_(151)-2.png) ![alt text](Screenshot_(146)-2.png) ![alt text](Screenshot_(147)-2.png) ![alt text](Screenshot_(149)-2.png)![alt text](em-1.PNG)