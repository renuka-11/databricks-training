# SQL NULL Functions Practice Assignment

## Overview

This assignment focuses on handling NULL values in SQL using different NULL-related functions and conditions. Practiced NULL checking, replacement functions, conditional logic, and NULL-safe calculations using real-world datasets.

## Topics Covered

### NULL Checking

* IS NULL
* IS NOT NULL

### NULL Replacement Functions

* IFNULL()
* COALESCE()

### NULL Comparison Function

* NULLIF()

### Real-Time NULL Handling

* Replacing missing values
* Handling NULL in calculations
* Avoiding divide-by-zero errors
* Filtering incomplete records

## Assignment Overview

Implemented and executed SQL queries on multiple tables containing NULL values.

Tables used:

* Employees
* Orders
* Products

Practiced:

* NULL filtering
* NULL replacement
* NULL-safe calculations
* Real-world NULL handling scenarios
* Advanced NULL function usage

## Tools Used

* MySQL
* [DB Fiddle](https://www.db-fiddle.com?utm_source=chatgpt.com) for query execution
* [GitHub](https://github.com?utm_source=chatgpt.com) for documentation and version control

## Project Files

* `schema.sql` – Table creation and sample data
* `queries.sql` – NULL function queries
* `output.txt` – Query outputs
* `README.md` – Project documentation

## Query Categories

### Basic NULL Queries

Performed filtering operations using NULL conditions.

Examples:

* Employees with NULL salary
* Orders with NULL discount
* Products with NULL category
* Records with missing manager details

### IFNULL() Practice

Used IFNULL() to replace missing values with default values.

Implemented:

* Replacing NULL salary with default amount
* Replacing NULL bonus values
* Replacing NULL stock values
* Handling missing order amounts

### COALESCE() Practice

Used COALESCE() to return the first non-NULL value.

Examples:

* Salary → Bonus → Default value
* Product price fallback values
* Customer payment calculations
* Employee income handling

### NULLIF() Practice

Used NULLIF() for conditional NULL handling.

Implemented:

* Converting matching values to NULL
* Avoiding divide-by-zero errors
* Replacing unwanted values with NULL
* Conditional NULL generation

### Real-Time Business Scenarios

Worked on practical NULL handling use cases.

Examples:

* Total earnings calculation
* Missing salary and bonus identification
* Orders with incomplete payment details
* Products with incomplete inventory information

### Advanced NULL Operations

Performed advanced NULL-safe calculations and filtering.

Examples:

* Combined salary and bonus calculations
* Nested NULL handling
* Multi-level fallback logic
* Conditional calculations using COALESCE() and NULLIF()

## Skills Improved

* NULL value handling in SQL
* Writing NULL-safe queries
* Using IFNULL(), COALESCE(), and NULLIF()
* Performing NULL-safe calculations
* Data cleaning techniques
* SQL filtering and conditional logic
* Error prevention in SQL operations

## Key Learning Outcomes

* Handled NULL values efficiently in SQL
* Used IFNULL() for default replacements
* Used COALESCE() for fallback values
* Used NULLIF() for conditional NULL generation
* Performed NULL-safe arithmetic operations
* Prevented divide-by-zero errors
* Filtered records using NULL conditions
* Worked with incomplete datasets effectively

## Highlights

* Practiced real-world NULL handling scenarios
* Improved understanding of SQL NULL behavior
* Learned multiple NULL replacement techniques
* Performed NULL-safe calculations
* Worked with incomplete and missing datasets
* Improved query structuring skills

## Final Outcome

Successfully completed SQL NULL Functions Practice Assignment covering:

* IFNULL()
* COALESCE()
* NULLIF()
* IS NULL / IS NOT NULL
* NULL-safe calculations
* Advanced conditional operations

Improved understanding of:

* SQL NULL behavior
* Data cleaning techniques
* Conditional SQL logic
* SQL error handling
* NULL-safe arithmetic operations
* Real-world database problem solving
