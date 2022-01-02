# SQL_For_Professionals



## Overview :
Structured Query Language (SQL) is a special-purpose programming language designed for managing data held in a
Relational Database Management System (RDBMS).

SQL --> Structured Query Language
NoSQL--> Not-only SQL


SQL comprises of 3 major sub-languages: <br >
1. Data Definition Language (DDL)----> create and modify 
2. Data Manipulation Language (DML)----> read,insert, update,delete.
3.  Data Control Language (DCL)----> contol the data

## Identifier :
    syntax rules for names of tables, columns, and other database objects.


## Data Types :
    The data type of a column defines what value the column can hold: integer, character, money, date and time, binary, and so on.



Each column in a database table is required to have a name and a data type.

An SQL developer must decide what type of data that will be stored inside each column when creating a table. The data type is a guideline for SQL to understand what type of data is expected inside of each column, and it also identifies how SQL will interact with the stored data.


- String Data Types: char,varchar,text,binary,varbinary etc..
- Numeric Data Types: bit, tinyint, int, bigint, decimal, float, 
- Date and Time Data Types: datetime, date,time.
- Other data types: sql_variant,xml,cursor,table.




## The SQL SELECT Statement

- The SELECT statement is used to select data from a database.

- The data returned is stored in a result table, called the result-set.

<b>SELECT Syntax :</b> <br>

    SELECT column1, column2, ...
    FROM table_name; 
            OR
    SELECT * FROM table_name;

## The SQL SELECT DISTINCT Statement
- The SELECT DISTINCT statement is used to return only distinct (different) values.

- Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

<b>SELECT DISTINCT Syntax :</b> <br>

    SELECT DISTINCT column1, column2, ...
    FROM table_name;












