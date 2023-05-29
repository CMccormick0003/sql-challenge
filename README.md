# sql-challenge

This project is divided into three parts: data modeling, data engineering, and data analysis.

## Data Modeling
1. Inspect the CSV files:  
departments.csv
dept_emp.csv
dept_manager.csv
employees.csv
salaries.csv
titles.csv

2. Sketch an Entity Relationship Diagram (ERD) of the tables. Use QuickDBD to make the ERD.

## Data Engineering
1. Create a table schema for each of the six CSV files. 
2. Specify the constraints including data types, primary keys, foreign keys.
3. For the primary keys, verify that the column is unique. 
4. If primary key column is not unique, create a composite key.  A composite key takes two primary keys to uniquely identify a row.
Note, Care needed to be taken to create the tables in the correct order to handle the foreign keys.
5. Import each CSV file into its corresponding SQL table.