# Understanding SQL

- So we finally get to the SQL database I know that it is really important being the most popular data base out there. it's kinda like mongodb with the schema and each entry having a id associated with it but what set it apart is its relations and tables.

- the reading didn't really go over relational data basing and mainly covered CRUD functionality and the types of SQL out there. so I'll really just talk about those guys for now and update as my knowledge of sql throughout the course.

     like mongoDB SQL is really just a collection of data with a language tied to it because the data bases have relations based of its table and like non
     relational databases it requires a schema.

     like mongodb that supports a noSQL languages Oracle, SQL Server,and MYSQL are a thing too so you have options on which one to use and works best for you.

it looks to me that the CRUD functions the same in mongoose but little more intertwined.

you got these tables and those tables hold the data then that table is correlated to the other tables. then those tables have rows that hold the data.
it looks like you have to define what colum you are targeting and then name them like so.

- side note.
I wonder if there are more operators and data types is there a boolean in SQL is that a thing?

## CRUD Commands

INSERT: used to add new data to a database.

SELECT: used to retrieve data from a database.

DELETE: used to delete data from a database.

UPDATE: used to modify existing data in a database.

## Data Types

VARCHAR stores character strings (such as names or addresses).

INTEGER: used to store numerical data.

DATE: used to store date values.

## Operators

AND: used to combine two or more conditions.

OR: used to specify that either of the two conditions can be true.

BETWEEN: used to specify a range of values.

## Creating tables

CREATE TABLE: used to create a new table in a database.

## Modifying tables

ALTER TABLE: used to modify an existing table in a database.

## Querying data

WHERE: used to filter the results of a SELECT statement based on specified conditions.

## Joining tables

INNER JOIN combines rows from two or more tables based on a common column.

LEFT JOIN: return all the rows from the left table and any rows from the right table that match them.

/
CREATE TABLE users ( id INTEGER PRIMARY KEY, username VARCHAR(255), password VARCHAR(255) );
/
