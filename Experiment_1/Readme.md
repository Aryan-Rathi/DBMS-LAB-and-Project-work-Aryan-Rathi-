Experiment 1: Data Definition and Manipulation 

Problem Statement
The objective is to design a database schema for an Employee-Department system and perform basic data manipulations.

Part A: Table Creation 

Table: DEPARTMENT
| Column Name | Data Type | Size | Attributes |
| :--- | :--- | :--- | :--- |
| Deptno | Number | 2 | Primary Key |
| Dname | Varchar2 | 15 | Not Null |

Table: EMPLOYEE
| Column Name | Data Type | Size | Attributes |
| :--- | :--- | :--- | :--- |
| EMPNO | Number | 4 | Primary Key |
| ENAME | Varchar2 | 20 | Not Null |
| JOB | Varchar2 | 20 | |
| MGR | Number | 4 | |
| HIREDATE | Date | | |
| SAL | Number | 10 | |
| COMM | Number | 7 | |
| DEPTNO | Number | 2 | Foreign Key |

Part B: Queries to Perform 

1. Create Employee_master table using the Employee table.

2. Delete all records from Employee_master where DeptNo is 10.

3. Update salary by 10% for DeptNo 20 in Employee_Master.

4. Alter SAL column to size (10,2).

5. Drop the Employee_master table.
