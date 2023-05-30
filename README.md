# SQL - Employee Data Challenge
This exercise is a research project about people whom a ficticious company employed during the 1980s and 1990s. All the source data are in six CSV files.

# Scope 
Design tables to hold the data from the CSV files
Import the CSV files into a SQL database
Analyze the data to answer questions about the data.

# Data Modeling
1. Inspect the CSV files:  
- departments.csv
- dept_emp.csv
- dept_manager.csv
- employees.csv
- salaries.csv
- titles.csv

2. Sketch an Entity Relationship Diagram (ERD) of the tables. ERD was made using QuickDBD.  ERD includes primary keys and foreign keys.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/c6bbabb6-a6da-4fb2-afdf-357a54b4401b)


# Data Engineering
1. Create a table schema for each of the six CSV files. 
2. Specify the constraints including data types, primary keys, foreign keys.
3. For the primary keys, verify that the column is unique. 
4. If primary key column is not unique, create a composite key.  A composite key takes two primary keys to uniquely identify a row. Note, Care needed to be taken to create the tables in the correct order to handle the foreign keys.  THe employees table must be created before the dept_emp, dept_manager or salaries tables because they include a forgein key that references the emp_no field in the employees table.
5. Import each CSV file into its corresponding SQL table.

## Data engineering SQL query code is available in the file: employee_sql_query.sql

# Data Analysis
## For each question below, the data analysis SQL query code is available in the file: employee_sql_query.sql.
A snipet is provided under each question as a representation of the query output.

## 1. List the employee number, last name, first name, sex, and salary of each employee.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/6e3f09c7-d623-42fc-be63-c9e800ef94bb)

## 2. List the first name, last name, and hire date for the employees who were hired in 1986.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/96a6c58b-27aa-4dc3-9991-1846eec8b510)

## 3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/ac43c27c-28c8-459b-b1b4-fa1c230aef0e)

## 4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/b66882c5-f8aa-4cf3-9fca-3fda9bd8af74)

## 5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/93f2e776-17aa-4458-872d-5e1f31bc9823)

## 6. List each employee in the Sales department, including their employee number, last name, and first name.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/c4df19af-c669-4cb7-8ef9-20aaa9557205)

## 7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/4ce9cdbb-c1f7-4504-986e-11d86864dc3a)

## 8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
![image](https://github.com/CMccormick0003/sql-challenge/assets/120672518/c78fd21e-8b4c-4a35-9e9c-85185c382b69)
