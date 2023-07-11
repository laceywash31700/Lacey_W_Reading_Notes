# Class-04 Reading Notes

## NoSQL vs SQL

> 1. ***What type of database is the best fit for the complex query intensive environment?***
> SQL is good for this because it has a rigid structure that relates to other tables and other content in the database.
>
> 2. ***What type of database is the best fit for hierarchical data storage?***
> SQL
>
> 3. ***Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.***
> So SQL is best scaled by increasing the amount of horsepower think of it like a engine ti have it be faster you need to increase the size of the server where
> as noSQL you want to increase the amount of engines in general meaning more servers as a whole.  
>

## SQL modeling techniques

> 1. ***Among data tables, what is a one-to-many relationship and how do we “relate” them?***
> A "One To Many" refers to a table that has a relation to multiple different tables in a database
>
> 2. ***Prior to designing your relational database, it might be useful to create__ a diagram__ of the database tables and their relationships.***
>
>
> 3. ***Explain the difference between a primary and foreign key.***
> Primary Keys uniquely identify the row in a table and usually have one key but can have more than one where as Foreign Keys are columns that match a primary
> key in another table.
>

## More on SQL Vs. NoSQL

> 1. ***How do we treat keywords and parameters differently in SQL syntax?***
> Keywords in SQL are reserved words that have a predefined meaning and functionality in the language. These keywords are used to define the structure of SQL
> statements and perform specific operations. Examples of SQL keywords include SELECT, INSERT, UPDATE, DELETE, JOIN, WHERE, ORDER BY, and GROUP BY, among
> other Parameters in SQL are values that are passed into a query to perform dynamic operations. Parameters are typically used in prepared statements or
> parameterized queries to enhance security and reusability of SQL code. They allow you to substitute specific values in a query without modifying the overall
> structure.
> Parameters are represented using placeholders, which are usually indicated with a question mark (?) or a named parameter notation (e.g., :param_name). The
> actual parameter values are provided separately, either programmatically or through user input, depending on the database programming interface or framework
> being used.
> 2. ***Define normalization within the context of schemas and data.***
> Normalization is just ensuring that any data we get how every we get it or data we might be missing is put into a format that fits into the table schema
>
> 3. ***Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.***
> In **one to one** relationship if we where to have a table that holds a person or user and another table that holds contact data now you need to connect them
> to one another and when you do connect them it is a one to one relationship now sometimes contact data can belong to multiple users making the relationship a
> **one to many** relation meaning that one table can be associated with multiple record same way you can have multiple products associated to multiple users.
> now in a situation where we are holding worker information where we have a user and those users have roles one user can have more than one role associated at
> there job this is where a **many to many** relationship come in where a third table can be used to sorta be the connection to user to there myriad of
> different roles they may have.

## Things I want to know about
