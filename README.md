# Task-8-Mastering-INNER-LEFT-RIGHT-FULL-JOINS

##  Objective
The goal of this task is to understand how to **combine data from multiple tables**
using different types of SQL JOINs such as **INNER JOIN, LEFT JOIN, RIGHT JOIN,
and FULL JOIN (simulated in MySQL)**.

##  Tools Used
- **Primary:** MySQL Workbench  
- **Alternatives:** PostgreSQL, BigQuery Sandbox
- 
##  Concepts Covered
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN (using UNION)
- Table Aliases
- Handling NULL values in joins
- Comparing join outputs
- Real-world business use cases of joins

##  Tables Used
### departments
Stores department details.

| Column Name | Description |
|------------|------------|
| department_id | Primary Key |
| department_name | Department Name |

### employees
Stores employee records.

| Column Name | Description |
|------------|------------|
| employee_id | Primary Key |
| employee_name | Employee Name |
| salary | Employee Salary |
| department_id | Foreign Key (can be NULL) |


## Join Operations Performed

### 1️⃣ INNER JOIN
- Fetches only employees who have a matching department
- Excludes records with no match on either side

### 2️⃣ LEFT JOIN
- Fetches all employees
- Displays NULL for employees without departments

### 3️⃣ RIGHT JOIN
- Fetches all departments
- Displays NULL for departments without employees

### 4️⃣ FULL JOIN (Simulated)
- Combines LEFT JOIN and RIGHT JOIN using UNION
- Fetches all employees and all departments, matched or not


