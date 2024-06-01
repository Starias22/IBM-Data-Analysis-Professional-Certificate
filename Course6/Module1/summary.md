# Module1: Getting started with SQL (Basic SQL)


## I- Introduction to databases

### Data

Data is a raw information collected to be organized and processed to make it meaningful.

### Databases

A database is a collection of data stored for easy acess, mamagement and updating

### DBMS

A DataBase Management System is a software designed to do all kind of operations with databases, including database creation, data insertion, update, retrieving, deleteing, etc.

There are 2 king of DBMS: relational databases and non relational databases.

#### Relational databases

Relational databases are databases where data are organized in a pre-defined structure, typically in a tabular format

EX: MySQL, PostgreSQL, IBM DB2, Oracle, etc

#### Relational databases

Non relational databases are databases with a flexible schema.

### SQL

#### Definition

SQL means Structured Query Language. It is the programming language used for relational databases.

SQL is a case-insensitive language.

#### Basic SQL commands

- `Create`, `Delete` a table
- `Insert` values into a table
- `Select` data from a table
- `Update` data in a table
- `Delete` data from a table

## II- Select statement

SELECT statement is used to retrieve data from a table

```SQL
SELECT * From <table>
```

```SQL
SELECT <col1> From <table>
```

```SQL
SELECT <col1>,  <col2>, <col3> From <table>
```

### WHERE CLAUSE

WHERE is used to specify a condition to be verified by rows that will be selected by the query.

```SQL
SELECT <col1> From <table> WHERE <condition>
```

### COUNT

Get the total number of rows that match a query.

```SQL
SELECT COUNT(*) From <table>
```

### DISTINCT

Used to avoid duplicate rows in the query result.

- Select rows with distinckt values for col

```SQL
SELECT DISTINCT <col> From <table>
```
- Select rows with distinct combinations of col1, col2, col3

```SQL
SELECT DISTINCT <col1>, <col2>, <col3> From <table>
```

- Select rows with distinct rows

```SQL
SELECT DISTINCT * From <table>
```

- Count the number of unique col values

```SQL
SELECT COUNT(DISTINCT <col1>) <col> From <table>
```

- Count the number of rows with distinck values for combination of col1, col2, col3

```SQL
SELECT COUNT(DISTINCT <col1>, <col2>, <col3>) From <table>
```

- Count the number of unique rows 

```SQL
SELECT COUNT(DISTINCT *) <col> From <table>
```

### LIMIT

Select just first n rows

```SQL
SELECT * FROM  <table> LIMIT <n>
```



## III- INSERT Statement

Used to insert new rows into a table.
- We can specify the colum and then the values of these columns. This allow us to set a value to only the columns we want.

```SQL
INSERT INTO  <table>  (<col1>,<col2>,...) VALUES (<val1>,<val2>,...)
```

- The columns may not be specified. In that case a value must be set for all the columns, and in the order of the order defined during the creation of the table.

 ```SQL
INSERT INTO  <table> VALUES (<val1>,<val2>,...)
```

## IV- UPDATE AND DELETE

### UPDATE

UPDATE is used to modify the value of an attribute in a table, with or without the consition to be verified by the rows to be updated.

```SQL
UPDATE <table> SET <col>=<val> [WHERE <condition>]
```

Without any condition specified, the changes are applied to all rows.

### DELETE

DELETE allows to remove all rows from a table with or without a condition to be verified by these rows to be removed.

```SQL
DELETE FROM  <table>  [WHERE <condition>]
```

Without any condition specified, all rows are deleted.
