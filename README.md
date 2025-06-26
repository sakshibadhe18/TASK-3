## Library Management System 
# Overview
This project is a Library Management System built using MySQL.
It consists of relational tables for Members, Books, and Issues.

# Data Retrieval Techniques
1️. Use SELECT * and specific columns
 SELECT * FROM Member; - Retrieves all columns from the Member table.
 SELECT name, phone FROM Member; - Retrieves only the name and phone columns.

2️. Apply WHERE, AND, OR, LIKE, BETWEEN
 WHERE - Filters results by a condition.
 AND - Combines multiple conditions that must all be true.
 OR - Matches any of the given conditions.
 LIKE - Searches for patterns ('%keyword%').
 BETWEEN - Filters data within a range.

3️. Sort with ORDER BY
 ORDER BY column_name ASC - Sorts results in ascending order.
 ORDER BY column_name DESC - Sorts results in descending order.
