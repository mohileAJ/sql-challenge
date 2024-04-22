# Employee SQL

Please run these commands within sqlite to build the schema of SQL tables and import the data from each CSV file into its corresponding SQL table: 

.read Schema.sql
.import --csv --skip 1 data/titles.csv titles
.import --csv --skip 1 data/departments.csv departments
.import --csv --skip 1 data/employees.csv employees
.import --csv --skip 1 data/salaries.csv salaries
.import --csv --skip 1 data/dept_emp.csv dept_emp
.import --csv --skip 1 data/dept_manager.csv dept_manager

Data Analysis: 
Please refer to the queries.sql file for Data Analysis queries. 

Kindly note, based on the retrieval of query results, we find that an employee may be a part of multiple departments.  Hence, such one-to-many relationship between the employees and departments tables shown in the ERD. 
