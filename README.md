# Project README

## Project Overview

This README provides an overview of the operations performed in this project. It describes the database schema and the SQL queries used.

## Table of Contents

- [Data Modeling](#data-modeling)
- [Data Engineering](#data-engineering)
- [Data Analysis](#data-analysis)

## Data Modeling

- Inspected the CSV files and sketched an Entity Relationship Diagram (ERD) of the tables.
- Used QuickDBD tool to create the ERD

## Data Engineering

- Created a table schema for each of the six CSV files.
  - Specified data types, primary keys, foreign keys, and other constraints.
  - Verified that primary key columns are unique; if not, created composite keys.
  - Created the tables in the correct order to handle foreign keys.
- Imported each CSV file into its corresponding SQL table.
  - Imported data in the same order as the tables were created.
  - Accounted for headers when doing the imports.

## Data Analysis

### Query 1
- Listed the employee number, last name, first name, sex, and salary of each employee.

### Query 2
- Listed the first name, last name, and hire date for the employees who were hired in 1986.

### Query 3
- Listed the manager of each department along with their department number, department name, employee number, last name, and first name.

### Query 4
- Listed the department number for each employee along with that employee’s employee number, last name, first name, and department name.

### Query 5
- Listed first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

### Query 6
- Listed each employee in the Sales department, including their employee number, last name, and first name.

### Query 7
- Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

### Query 8
- Listed the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).



