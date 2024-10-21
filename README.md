# Pewlett Hackard Employee Database Challenge

## Overview

As a new Data Engineer at Pewlett Hackard (a fictional company), your first major task is to research the company's employees from the 1980s and 1990s. The remaining employee database consists of six CSV files. The project involves:

- **Data Modeling**: Designing tables and creating an Entity Relationship Diagram (ERD).
- **Data Engineering**: Importing data into SQL tables and managing table schemas.
- **Data Analysis**: Writing queries to answer key business questions.

## Project Steps

### 1. Data Modeling

- Inspect the CSV files to understand their structure.
- Sketch an **Entity Relationship Diagram (ERD)** to visualize the relationships between tables. Tools like [QuickDBD](https://www.quickdatabasediagrams.com/) can be used for this purpose.

### 2. Data Engineering

- Create a table schema for each of the six CSV files, ensuring the following:
  - Define **data types**, **primary keys**, **foreign keys**, and other constraints.
  - Ensure **unique** primary keys or create a **composite key** when necessary.
  - Import each CSV file into its corresponding SQL table.
- Import order matters! Import the data in the same order as the corresponding tables were created, and ensure headers are handled properly.

### 3. Data Analysis

Once the data is imported, perform SQL queries to answer the following questions:

- **Employee Details**: List the employee number, last name, first name, sex, and salary of each employee.
- **Employees Hired in 1986**: List the first name, last name, and hire date for employees hired in 1986.
- **Department Managers**: List the manager of each department, including their department number, department name, employee number, last name, and first name.
- **Employee Department Assignment**: List the department number for each employee along with their employee number, last name, first name, and department name.
- **Specific Employees**: List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- **Sales Department**: List each employee in the Sales department, including their employee number, last name, and first name.
- **Sales & Development Departments**: List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- **Last Name Frequency**: List the frequency counts, in descending order, of all the employee last names (i.e., how many employees share each last name).

## Hints & Tips

- Be mindful of the **import order** of tables to avoid foreign key constraint errors.
- **Data integrity** is critical. Ensure that the primary keys and foreign keys are correctly linked.
- When importing CSV files, be sure to **account for headers** to avoid misalignment in the data.

