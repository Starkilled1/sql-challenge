# sql-challenge

This repository holds the code used to complete a data engineering challenge focused on a fictional company named Pewlett Hackard. The challenge revolves around analyzing employee data.

### Objective

The objective of this repository is to:

1. Design tables to store data extracted from six CSV files. 
2. Import the CSV data into a SQL database.
3. Write SQL queries to answer questions about the imported data.

### Files

This repository contains the following files:

* *ERD_Diagram.png*: This file contains an image depicting the final Entity-Relationship Diagram (ERD) for the project schema.
* *Schema.sql*: This file contains the SQL statements required to create the database tables based on the provided CSV files.
* *Data_Analysis_Queries.sql*: This file contains all the SQL queries written to answer questions about the employee data. The queries in this file address the following:
    * List all employees with their employee number, last name, first name, sex, and salary.
    * List employees hired in 1986, including their first name, last name, and hire date.
    * List department managers with their department number, department name, employee number, last name, and first name.
    * List employee department information, including employee number, last name, first name, and department number.
    * List employees with the first name "Hercules" and a last name starting with "B", including their first name, last name, and sex.
    * List all employees in the Sales department, including their employee number, last name, and first name.
    * List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
    * List the frequency counts of employee last names (number of employees sharing each last name) in descending order.
* *output*: This folder stores the output CSV files generated by running the queries.sql file.

### Explore Further

This repository provides a starting point for exploring data modeling, data engineering, and data analysis with SQL. We encourage you to delve deeper by:

* Modifying the provided SQL queries to answer your own questions about the employee data.
* Trying out different data analysis techniques to uncover further insights from the data.
* Experimenting with additional SQL features to enhance your data manipulation skills.