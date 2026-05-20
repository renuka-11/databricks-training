# DATE & TIMESTAMP FUNCTIONS IN MYSQL (Practice Assignment)

## Overview

This assignment focuses on MySQL Date and Timestamp functions using real-world order data. Practiced date extraction, formatting, filtering, arithmetic operations, and business logic queries using SQL.

## Objective

Learned and practiced:

* Date extraction and formatting
* Timestamp handling
* Date arithmetic operations
* CASE-based business logic
* Real-world order data analysis using SQL

## Database Schema

### Table: `orders`

```sql
CREATE TABLE orders(
    order_id INT PRIMARY KEY,
    customer_name VARCHAR(50),
    order_date DATE,
    order_timestamp TIMESTAMP,
    delivery_date DATE,
    order_amount DECIMAL(10,2)
);
```

## Topics Covered

### Current Date & Time Functions

* CURDATE()
* CURRENT_TIME()
* NOW()

### Date Extraction Functions

* YEAR()
* MONTH()
* DAY()

### Date Naming Functions

* MONTHNAME()
* DAYNAME()

### Filtering by Date

* Weekend filtering
* Weekday filtering
* Month-based filtering

### Date Arithmetic

* DATE_ADD()
* DATE_SUB()

### Difference Calculations

* DATEDIFF()
* TIMESTAMPDIFF()

### Date Boundary Functions

* LAST_DAY()
* First day calculation

### Formatting Functions

* DATE_FORMAT()
* DD-MM-YYYY formatting
* Full timestamp formatting

### CASE-Based Business Logic

* Financial year calculation
* Date-based classification

## Key Queries Practiced

* Retrieved current system date and time
* Extracted year, month, and day from order dates
* Identified month names and weekdays
* Filtered weekend and weekday orders
* Calculated delivery durations
* Performed timestamp difference analysis
* Formatted dates for reporting
* Implemented financial year classification logic

## Tools Used

* MySQL
* DB Fiddle for query execution
* GitHub for version control and documentation

## Project Files

* `schema.sql` – Database schema and sample records
* `queries.sql` – SQL query solutions
* `output.txt` – Query outputs
* `README.md` – Project documentation

## Skills Gained

* SQL date and time manipulation
* Business query building using SQL
* Data formatting techniques
* Time-based analytics
* CASE-based logic implementation
* Query optimization thinking

## Learning Outcomes

* Worked with MySQL date and timestamp functions
* Extracted and transformed date components
* Performed date and time calculations
* Built business and financial logic queries
* Formatted data for reporting systems
* Analyzed real-world order datasets

## Highlights

* Practiced real-world order analysis
* Learned financial year calculation logic
* Improved date difference calculations
* Built formatted reporting queries
* Strengthened SQL analytical thinking

## Final Outcome

Successfully completed practice on MySQL Date and Timestamp functions used in:

* E-commerce order systems
* Financial reporting
* Delivery tracking systems
* Business analytics dashboards

Improved understanding of:

* Date and time functions
* SQL analytical queries
* Business rule implementation
* Reporting and formatting techniques
* Real-world SQL problem solving
