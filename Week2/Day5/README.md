# SQL JOINS PRACTICE ASSIGNMENT

## Overview

This assignment focuses on SQL JOIN operations using a real-world database containing employees, departments, and projects. Practiced different types of joins and their usage in relational database analysis.

## Objective

Learned and practiced:

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN (simulated in MySQL)
* SELF JOIN
* Multi-table relationships
* Real-world data retrieval using joins

## Database Schema

### Table: `employees`

```sql id="y2u2c3"
CREATE TABLE employees(
    emp_id INT PRIMARY KEY,
    emp_name VARCHAR(50),
    manager_id INT,
    dept_id INT
);
```

### Table: `departments`

```sql id="m7bk7u"
CREATE TABLE departments(
    dept_id INT PRIMARY KEY,
    dept_name VARCHAR(50)
);
```

### Table: `projects`

```sql id="8xh36i"
CREATE TABLE projects(
    project_id INT PRIMARY KEY,
    project_name VARCHAR(50),
    emp_id INT
);
```

## Join Types Practiced

### INNER JOIN

Retrieved matching records from multiple tables.

Examples:

* Employees with departments
* Employees with managers
* Employees assigned to projects

### LEFT JOIN

Retrieved all records from the left table and matched records from the right table.

Examples:

* Employees without departments
* Employees without projects
* Department-wise employee count

### RIGHT JOIN

Retrieved all records from the right table and matched records from the left table.

Examples:

* All departments including empty departments
* All projects including unassigned projects

### FULL OUTER JOIN (Simulated)

Implemented FULL OUTER JOIN in MySQL using:

* LEFT JOIN
* UNION
* RIGHT JOIN

Examples:

* Employees without departments
* Departments without employees

### SELF JOIN

Used SELF JOIN for hierarchical relationships.

Examples:

* Employee and manager mapping
* Reporting structure analysis

## Query Categories

### Employee and Department Analysis

* Mapped employees to departments
* Found employees without departments
* Counted employees department-wise

### Employee and Manager Analysis

* Displayed manager names
* Built reporting hierarchy
* Practiced self join queries

### Project Assignment Analysis

* Employees assigned to projects
* Projects without employees
* Full project mapping

### NULL Handling with Joins

* Employees without departments
* Employees without projects
* Departments without employees
* Worked with NULL values in joins

### Aggregation with Joins

* Department-wise employee count
* Project-wise employee mapping
* GROUP BY with JOIN operations

## Tools Used

* MySQL
* [DB Fiddle](https://www.db-fiddle.com?utm_source=chatgpt.com) for query execution
* [GitHub](https://github.com?utm_source=chatgpt.com) for version control and documentation

## Project Files

* `schema.sql` – Database schema and sample data
* `queries.sql` – SQL query solutions
* `output.txt` – Query outputs
* `README.md` – Project documentation

## Skills Gained

* SQL JOIN operations
* Relational database understanding
* Multi-table query writing
* Data relationship mapping
* NULL handling in joins
* Hierarchical data analysis
* Real-world database querying

## Key Learning Outcomes

* Worked with multiple related tables
* Practiced INNER, LEFT, and RIGHT JOIN
* Simulated FULL OUTER JOIN in MySQL
* Built manager–employee hierarchy queries
* Analyzed project assignments
* Performed grouped analysis using JOIN + GROUP BY
* Improved relational database concepts

## Highlights

* Practiced real-world HR and project database queries
* Learned SELF JOIN for hierarchy mapping
* Implemented NULL-safe queries
* Simulated FULL OUTER JOIN logic
* Improved database design understanding

## Final Outcome

Successfully completed SQL JOIN practice exercises covering:

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL OUTER JOIN simulation
* SELF JOIN
* Multi-table analysis

Improved understanding of:

* Relational databases
* SQL joins and relationships
* Backend database querying
* Data analysis using SQL
* Real-world SQL problem solving

