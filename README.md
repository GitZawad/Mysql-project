# **Employee Management System Queries (MySQL Project)**

This project is a MySQL-based solution designed to showcase common operations on employee data. It demonstrates the use of relational database operations, focusing on employee details, salaries, department assignments, and hierarchical relationships like supervisors.

The project was done using the employees database from https://github.com/datacharmer/test_db

## **Features**

*This project includes solutions to the following questions:*

**- Show every employee’s ID, name, and salary.**

**- Count the number of employees in each department.**

**- Show employees with the same or higher salaries than the average salary in each department.**

**- Show the name of employees who joined the company last in each department.**

**- Show the name of each employee, their hire date, and their supervisor.**

## **Database Structure**

*The project uses the following key tables:*

**employees:** Stores employee details, including emp_no, first_name, last_name, and hire_date.

**salaries:** Stores salaries for employees, linked via emp_no.

**dept_emp:** Maps employees to departments via dept_no and emp_no.

**departments:** Stores department details such as dept_no and dept_name.

**dept_manager:** Tracks department managers, linking dept_no with their emp_no.

