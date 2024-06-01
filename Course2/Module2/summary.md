# Week 2: The Data Ecosystem

**Data:** An organized information that is processed to make it meaningful.

**Data Analysis ecosystem:** It includes the infrastructures, tools, software, frameworks, and processes needed for data analysis.

## Data Structures

- **Structured Data:** They have a well-defined structure, often representable in rows and columns, also called tabular format.
  - SQL databases (PostgreSQL, MySQL, etc.)
  - Spreadsheets (Google, Excel, etc.)

- **Semi-structured Data:** Have some organizational properties but do not have a fixed or rigid schema.
  - JSON, XML, emails, zip files

- **Unstructured data:** Cannot be organized in tabular format, does not have an easily identifiable structure.
  - Web pages, PDF files, images, audio, videos, PowerPoint presentations

## File Formats

- **Delimited text file formats:** Store the data as text, each value delimited by a character, which can be:
  - Comma: Comma Separated Values (CSV): `.csv` extension
  - Tabulation character: Tab Separated Values (TSV): `.tsv` extension
  - Other character

- **Microsoft Excel Spreadsheet:** `.xlsx` and `.xls`
- **Extensible Markup Language XML:** `.xml`
  - Self-descriptive, human-readable, with tags like HTML, programming language, and platform independent.

- **PDF:** Portable Document File: `.pdf` extension
- **JSON:** JavaScript Object Notation
  - Store data like key-values pairs language and platform independent human-readable.

## Data Sources

Data sources: are the origins the data are collected from for analysis.

- **Relational databases:** Use tabular format to store structured data, each line/row/entry is called an observation.
  - Examples of relational database systems: SQL Server, MySQL, PostgreSQL, IBM DB2, Oracle

- **Flat files:** Store data as text, each row or line is an observation.
  - Values are delimited by a character (e.g., `.csv`, `.tsv`)

- **Spreadsheets:** They also store data in a tabular format, each worksheet represents a table.
  - Examples: `.xsl`, `.xlsx`
  - Platforms/Software: Microsoft Excel, Google Sheet, LibreOffice Calc

- **APIs and web services:** Listen for incoming requests from client or application and respond to that request by providing text files, XML, JSON, HTML, etc.
  - Examples:
    - Facebook and Twitter for sentiment analysis
    - Stock market APIs (e.g., Yahoo Finance) for finance

- **Web scraping/web harvesting/web extraction:** Extract data from websites.
  - Tools: BeautifulSoup, Scrapy, Selenium, pandas

- **Data Streams and Feeds**

They allow to ggregate data from instruments, IoT, web, social media, computer programs, etc.

## Programming Languages for Data Professionals

- SQL, Python, R, Java, Unix/Shell scripting, PowerShell

## Data Repositories

A data repository is a data library or archive. It may be a DBMS or a set of DBMs where data are collected from various sources, organized, and isolated for business operations and data analysis.

Data repositories can be categorized into 3 main types:

### Database

A database is a collection of information organized and stored to facilitate efficient retrieval, manipulation, and management.

#### DBMS (Database Management System)

Software program used for all operations with data in a database, including creating, retrieving, updating, and removing.

#### Types of Databases

There are two main types of databases

##### Relational databases

- Data are organized in tabular format with rows and columns, suitable for structured data.
- They are also called SQL databases(Structured Query Language)
- They are suitable for structured data
- Examples:

  - SQL Server, MySQL, PostgreSQL, IBM DB2, Oracle
  - On cloud: Amazon RDB, Google SQL, IBM DB2, Oracle Cloud, Azure SQL

##### Non-relational databases/NoSQL
  
Non-relational databases/NoSQL (Not Only SQL) are databases where information is organized in a flexible structure and no pre-defined format.

They are suitable for unstructured and semi-structured data.

There are 4 Types of NoSQL Databases

- **Key-value store:** Stores information in a key-value pairs way. Suitable for storing user sessions, preferences information, cache memory information.
  - Examples: Redis, MemCached, DynamoDB

- **Document-based:** Each record is a document.
  - Examples: MongoDB, DocumentDB, CouchDB, Cloudant

- **Column-based:** Stores data in cells grouped as columns of data instead of rows.
  - Examples: Cassandra, Apache HBase

- **Graph store:** Uses a graphical model to represent information. Suitable for connected data.
  - Examples: Neo4J, CosmosDB

### Datawarehouse

It is central data repository which merges data from various sources into a comprehensive format for their use for business operations and data analytics.

- Uses the process of ETL (Extract, Transform, Load): an automated process of extraction of the data form various data sources, transforming the data into a usable format, and loading the data into the repository.

#### Data Mart

A subsection of data warehouse built for use in a specific business function or purpose.

#### Data Lake

A storage repository built for storing a large amount of data from structured, semi-structured, and unstructured data sources.

#### Data Pipeline

The journey of moving data from a source to another, including ETL.

### Big Data store

Big data stores are infrastructures for storage and distributed computations with large volume data.

## Big Data basics

### Big data implies 5Vs

- Velocity: The speed of the data stream: so fast.
- Variety: The data comes from various sources and have different structures.
- Volume: A large amount of data.
- Veracity: The quality and originality of the data.
- Value: Gain value (profit, social, and medical benefit) from data.

### Big Data Processing Tools

- Hadoop: A collection of tools for distributed storage and processing of big data.
- Hive: A data warehouse for data querying and analysis.
- Apache Spark: A framework for distributed analysis of complex data in real-time.
