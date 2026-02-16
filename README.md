1. The Overview of Tasks

The second assignment covered the creation, management, and deletion of Oracle Pluggable Databases (PDBs) as part of hands-on exercises in Oracle Database administration. The tasks that were completed include:
Familiarizing with the database structure by doing several researches.
Creating and deleting the PDB and user.
The management of PDB.
Usage of Oracle Enterprise Manager (OEM).

2. The Oracle Environment That Was Used

The Oracle Database Version i used was Oracle Database 21c (which required a 8+ RAM)
The tools that were involved in demonstrating the tasks were: CMD(Administrator), SQL Developer, Oracle Enterprise Manager (OEM)

3. Explanations of each task

Am starting with the tools i used i had the SQL Developer which helped me in the writing of the sql queries, in management and performing most of the database operations and also it allowed the connection to CDB or the specific PDBs.

I used also the Oracle Database Express 21c which is the web based interface for monitoring and also managing the databases operations, it is useful in checking the pdb status, opening or closing databases and monitoring the database performance.

So the first task i created a new pluggable database (PDB)
the PDB name was IN_PDB_27779
the Username inside PDB nairoti_plsqlauca_27779
Identified by nai1234


Step1 I connected to the cdb as sysdba.
Step2 I created the PDB using CREATE PLUGGABLE DATABASE.
Step3 I opened the PDB using ALTER PLUGGABLE DATABASE ... OPEN.
Step4 I created a user inside the PDB and granted required privileges.
Step5 I verified the PDB status (opened) and user creation.


So the second task i created and deleted a temporary PDB the temporary PDB name was in_to_delete_pdb_27779

Steps1 I created the temporary PDB
Steps2 I verified if it is existing
Steps3 I closed and dropped the PDB with including the datafiles 
Steps4 I confirmed deletion

So the third task i operated the Oracle Enterprise Manager (OEM) 
because we use the localhost i took the link provided when i was installing the database (https://localhost5500/em) and i logged in using my credentials username and password


4. The challenges i faced

While demonstrating all that i met some challenges where i could write a querry and the result would come as an error because i had forgotten  to ensure the correct container connection to create users inside the PDB required setting alter session set container=....

in resolving the challenges i faced i used some youtube videos explaining it properly this is the link (https://www.youtube.com/watch?v=UI59zy_WLTQ).

5. Integrity statement

I Igirimbabazi Nairot hereby declare that this assignment was done by me  with the help of some youtube videos which helped me to fully understand and familiarize with the database. 
