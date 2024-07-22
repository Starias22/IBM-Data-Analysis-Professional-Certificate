# Module 2: Introduction to Relational Databases and Tables

## Relational Database Concepts

## Types of SQL Statements: DDL vs DML

### DDL: Data Definition Language

This includes the set of SQL statements used to create, modify or drop database objects such as table.

Common DDL are:

- CREATE
- ALTER
- TRUNCATE
- DROP

### DML: Data Manipulation Language

A set of statments used to read and update data: CRUD

There are:
- SELECT
- INSERT
- UPDATE
- DELETE

## CREATE TABLE

## ALTER, DROP, TRUNCATE

### ALTER TABLE

used to
- add or remove columns
- modify the data type of columns
- add or remove keys
- add or remove constraints

### DROP TABLE

It removes the table from the database

```SQL
DROP TABLE <table>
```

### TRUNCATE TABLE

```SQL
TRUNCATE TABLE <table>
```

It removes all rows from the table without removing the table itself. The difference with delete is that it reset identity keys.

## Cloud databases

### Importance

Cloud databases :

- easy to use, via API, web interface, cloud or remote apps
- scalable and economic
- recoverable

### Examples

- IBM DB2
- Databases for PostgreSQQL
- Oracle Database Cloud Service
- Microsoft Azure SQL database
- Amazon Relational Database Services(RDS)