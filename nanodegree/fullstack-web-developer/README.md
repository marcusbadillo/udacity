# Full Stack Web Developer Nanodegree

## Primary Key

The primary key is the unique identifier for the entire row, referring to one or more columns.
If there are more multiple columns for the primary key, then the set of primary key columns is known as a composite key.

## Foreign Key

A primary key in another (foreign) table.
Foreign keys are used to map relationships between tables
Relationships between tables are encoded using foreign keys

## SQL Cheatsheet

![picture](nanodegree/fullstack-web-developer/media/SQL-Basic-Cheat-Sheet-1.png)

1. Every relational database system has its own particular implementation of SQL. TRUE

2. On a joined select query that joins a vehicles table and a drivers table, the execution plan traverses the vehicles table and encounters a row with a driver_id that does not have a matching record in the foreign (drivers) table. If it is an INNER JOIN query, then the execution plan would skip that row and not add it to the query's output.

* INNER JOIN -  between two tables returns rows of data that exist across all joined tables, excluding rows that may only exist in one of the tables but not the other table.

* OUTER JOIN - return every row that exists in the left (in a left outer join) or right (in a right outer join) joined table, while rendering NULL values on rows whose foreign key does not match a record in the other (right or left) table.

* The "left" table refers to the table to the left of the JOIN statement in the query, whereas the "right" table refers to the table to the right of the JOIN statement in the query.
