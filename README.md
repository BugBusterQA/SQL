# SQL



Structured Query Language (SQL) is a standard programming language used to manage and manipulate relational databases. SQL queries are used to perform various actions on the database, such as retrieving, updating, or deleting data. Below are some common SQL queries used in database testing

SELECT - The SELECT statement is used to retrieve data from one or more tables in the database.
INSERT - The INSERT statement is used to add new records to a table.
UPDATE 
DELETE

### SQL SELECT examples:

Retrieving all data from a table:
SELECT * FROM table_name;

Retrieving specific columns from a table:
SELECT column1, column2, ... FROM table_name;

Retrieving data with condition:
SELECT column1, column2, ... FROM table_name
WHERE ID=13;

Retrieving data with sorting:
SELECT column1, column2, ... FROM table_name
ORDER BY column_name ASC|DESC;

Retrieving data with grouping:
SELECT column1, column2, ... FROM table_name
GROUP BY column_name;

### SQL UPDATE example:
UPDATE tableName SET field1=new_value1 WHERE condition = value


