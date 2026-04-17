# Pewlett Hackard Employee SQL Analysis

## Overview
A SQL data modeling, engineering, and analysis project reconstructing the employee 
database of Pewlett Hackard (a fictional company) from six CSV files covering 
employees from the 1980s and 1990s. Includes ERD design, schema creation, data 
import, and exploratory SQL queries.

---

## Process

### Data Modeling
- Inspected all six CSV files to understand structure and relationships
- Designed an Entity Relationship Diagram (ERD) mapping table relationships, 
  primary keys, foreign keys, and constraints

### Data Engineering
- Created table schemas for all six CSV files with appropriate data types, 
  primary keys, foreign keys, and constraints
- Built tables in dependency order to handle foreign key relationships
- Imported all CSV files into corresponding SQL tables

### Data Analysis
Answered the following questions using SQL queries:
- Employee number, name, sex, and salary for all employees
- Employees hired in 1986
- Department managers with department and employee details
- Department assignments for all employees
- Employees named Hercules with a last name beginning with B
- All employees in the Sales department
- All employees in Sales and Development departments
- Frequency count of all employee last names in descending order

---

## Tech Stack
- PostgreSQL
- pgAdmin / QuickDBD
- CSV data import

---

## Repository Contents
| Folder/File | Description |
|-------------|-------------|
| `EmployeeSQL/` | Schema files, query scripts, and source CSVs |
| `EmployeeSQL/schema.sql` | Table creation scripts |
| `EmployeeSQL/queries.sql` | Data analysis queries |
| `EmployeeSQL/ERD.png` | Entity Relationship Diagram |
