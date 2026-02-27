# MySQL Daily Practice Journey

This repository documents my **day-wise MySQL learning journey**, starting from basic concepts and gradually moving towards advanced SQL topics with hands-on practice.



##  Day 01 – Basic MySQL Practice

### Focus
Understanding **basic database operations** and writing first SQL queries confidently.

### Topics Covered
- What is a database
- Difference between database and table
- How MySQL stores data in tabular format

### Database Operations
- CREATE DATABASE
- USE database
- SHOW DATABASES

### Table Operations
- CREATE TABLE
- Understanding columns and data types
- DESC table_name
- SHOW TABLES

### Queries Practiced
- INSERT INTO
- SELECT *
- SELECT column_name
- WHERE
- LIMIT



##  Day 02 – Filtering & Sorting Data

### Topics Covered
- WHERE clause
- AND / OR conditions
- ORDER BY (ASC, DESC)
- DISTINCT
- LIMIT

### Learnings
- Filtering records using conditions
- Sorting query results
- Fetching unique values
- Limiting output rows



## Day 03 – Aggregate Functions & GROUP BY

### Topics Covered
- COUNT
- SUM
- AVG
- MIN
- MAX
- GROUP BY

### Practice Summary
- Calculated total students
- Found average, minimum, and maximum marks
- Department-wise analysis



##  Day 04 – WHERE, ORDER BY, LIMIT, DISTINCT

### Practice Summary
- Advanced filtering using WHERE
- Sorting data using ORDER BY
- Limiting records using LIMIT
- Removing duplicates using DISTINCT
- Combined conditional queries

### Table Used
- students



##  Day 05 – LIKE, IN, NOT IN, BETWEEN

### Topics Covered
- LIKE (pattern matching)
- IN
- NOT IN
- BETWEEN

### Practice Summary
- Pattern-based queries
- Filtering multiple values
- Excluding specific records
- Range-based filtering
- Real-world student queries



##  Day 06 – INNER JOIN

### Topics Covered
- INNER JOIN
- Table aliases
- Joining multiple tables

### Practice Summary
- Created departments table
- Joined students and departments
- Applied filters on joined data



##  Day 07 – LEFT JOIN

### Topics Covered
- LEFT JOIN
- NULL values in joins

### Practice Summary
- Retrieved all records from left table
- Identified missing relationships
- Practiced interview-style queries
  


##  Day 08 – GROUP BY & HAVING

### Topics Covered
- GROUP BY with aggregate functions
- HAVING clause

### Practice Summary
- Department-wise student count
- Average and maximum marks
- Filtering grouped data


##  Day 09 – Subqueries (Nested Queries)

### Topics Covered
- Subqueries
- Single-row subqueries
- Subqueries with AVG and MAX
- Correlated subqueries

### Practice Summary
- Students scoring above overall average
- Student(s) with highest marks
- Department with highest average marks
- Students scoring above department average
- Department(s) with maximum students

##  Day 10 – Constraints & Keys

### Topics Covered
- PRIMARY KEY
- FOREIGN KEY
- UNIQUE
- NOT NULL
- CHECK

### Practice Summary
- Created departments table with PRIMARY and UNIQUE constraints
- Created students table with NOT NULL and CHECK constraints
- Linked tables using FOREIGN KEY
- Inserted valid data respecting constraints
- Understood parent–child table relationship


## Conclusion

This 10-day journey helped me build a **strong foundation in MySQL**, covering core SQL concepts, relational database design, and interview-relevant queries.

## Day 11 – JOIN Operations (INNER JOIN)

Today I practiced **INNER JOIN**, which is used to retrieve data from **multiple related tables** in MySQL.



### What I Learned
- What is a JOIN in SQL
- Why JOIN is required in relational databases
- How tables are linked using PRIMARY KEY and FOREIGN KEY
- How INNER JOIN returns only matching records



### Topics Covered
- INNER JOIN
- Table aliases
- INNER JOIN with WHERE clause
- INNER JOIN with GROUP BY



### Practice Summary
- Joined `students` and `departments` tables using INNER JOIN
- Retrieved student details along with department names
- Filtered joined data using WHERE condition
- Calculated department-wise student count and average marks
- Understood real-world use of JOIN queries

## Day 12 – RIGHT JOIN & FULL JOIN (MySQL)

Today I practiced **RIGHT JOIN** and understood the concept of  
**FULL OUTER JOIN** in MySQL.



### What I Learned
- RIGHT JOIN returns all records from the **right table**
- NULL values appear when no matching record exists
- MySQL does not support FULL JOIN directly
- FULL JOIN can be simulated using **LEFT JOIN + UNION + RIGHT JOIN**



### Tables Used
- students  
- departments  



### Queries Practiced
- RIGHT JOIN between students and departments  
- Finding departments with no students  
- Simulating FULL OUTER JOIN using UNION  



### Summary
- Learned how to handle missing relationships  
- Improved JOIN logic for interview questions  
- Strengthened relational database understanding  

# Day 13 – Views & Indexes (MySQL)

Today I practiced **Views** and **Indexes** to understand how MySQL  
handles reusable queries and improves query performance.


## What I Learned
- What is a VIEW and why it is used
- Creating and using views
- Updating data through views
- What is an INDEX
- How indexes improve query performance


## Topics Covered
- CREATE VIEW
- SELECT from VIEW
- DROP VIEW
- CREATE INDEX
- SHOW INDEX


## Practice Summary
- Created views for student and department data
- Retrieved data using views instead of complex queries
- Created indexes on frequently searched columns
- Understood basic performance optimization concepts

# Day 14 – Foreign Key & Data Integrity

Today I practiced working with **FOREIGN KEY constraints** in MySQL.

## What I did
- Verified parent table (`departments`) data
- Inserted records into child table (`students`)
- Fixed foreign key issues by ensuring correct table mapping
- Successfully retrieved student records

## Key Learning
- Parent table must contain referenced values before inserting into child table
- Table name consistency is critical in foreign key relationships

## Tables Used
- departments
- students
