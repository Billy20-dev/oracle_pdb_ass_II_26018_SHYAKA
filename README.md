# oracle_pdb_ass_II_26018_SHYAKA

. Student Information
Name: SHYAKA Billy
Student ID: 26018

. Repository Link
https://github.com/Billy20-dev/oracle_pdb_ass_II_26018_SHYAKA.git

. Oracle Environment Used
Operating System: Windows os
. Database: Oracle Database 
. Tools Used: SQL*Plus, Oracle Enterprise Manager (OEM), GitHub

# Task 1: Create a New Pluggable Database (PDB)
. PDB Created: Billy_pdb_26018

. Steps Performed:
*	Connected to Oracle as SYSDBA using SQL*Plus.
*	Checked existing PDBs.
*	Created a new PDB named Billy_pdb_26018.
*	Opened the PDB and saved its state.
*	Switched session into the PDB.
*	Created a user inside the PDB for future class work.
  
. User Created Inside PDB
Username: billy_plsqlquiz_26018
Password: Billy123

. Privileges Granted
*	CONNECT
*	RESOURCE
*	CREATE SESSION
*	CREATE TABLE
*	UNLIMITED TABLESPACE
  
. Evidence (Screenshots Included)
. Screenshots are included in the screenshots/ folder showing:
*	PDB creation
*	PDB open state
*	User creation and privileges
*	Successful login as the created user
  
# Task 2: Create and Delete a Temporary PDB
. Temporary PDB Created and Deleted: bi_to_delete_pdb_26018
Steps Performed:
*	Connected as SYSDBA.
*	Created the temporary PDB bi_to_delete_pdb_26018.
*	Verified that the PDB existed.
*	Closed the PDB.
*	Dropped the PDB completely including datafiles.
*	Verified that the PDB no longer exists.
  
. Evidence (Screenshots Included)
Screenshots are included in the screenshots/ folder showing:
*	Temporary PDB creation
*	Temporary PDB existence confirmation
*	Deletion command results
*	Confirmation that the PDB no longer exists
  
# Task 3: Oracle Enterprise Manager (OEM)
. Steps Performed:
*	Configured and accessed Oracle Enterprise Manager (OEM).
*	Logged into the OEM dashboard.
*	Verified that the dashboard reflected the Oracle environment.
*	Verified that completed PDB tasks were visible.
  
. Evidence (Screenshot Included)
Screenshot of the OEM dashboard showing my username is included in screenshots/ folder.

.Issues Encountered
None

.Integrity Statement
I, SHYAKA Billy (26018), confirm that this assignment was completed individually.
All screenshots and results included in this repository are from my own execution in Oracle Database.
Folder Structure

. oracle_pdb_ass_II_26018_billy/
│
├── README.md
└── screenshots/
    ├── task1_pdb_creation.png
    ├── task1_pdb_open.png
    ├── task1_user_created.png
    ├── task2_temp_pdb_created.png
    ├── task2_temp_pdb_deleted.png
    └── oem_dashboard.png


