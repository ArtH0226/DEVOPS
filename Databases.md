# Databases

## What is a Database?
- Definition: A shared collection of related data used to support the activities of a particular organization
- Purpose: To a Sepcific piece (or group) of information quickly.
- Examples?
- Database Properties
  - A collection of data elements (facts) represnting real-world information
  - It is logical, coherent and internally consistent.
  - Well-designed, built and populated with data for a sepcific purpose. 
  - Each data item is stored in a field
  - A combination of fields makes up a table

## Benefits of a Databse
- Self-describing nature of a database system
- Insulation between program and data
- Support for multiple views of data 
- Sharing of data and multiuser system
- Control of data redundancy
- Data Sharing 
- Enforcement of integrity constraints
- Restriction of unauthorized access
- Data independence Transaction processing
- Provision for multiple views of data 
- Backup and recovery facilities

## Relational Databases
- Fundamental Concepts.
  - Relation
  - Table
  - Cloumn
  - Domain
  - Record
- Properties of a Tables
  - Distinct Name
  - No duplicate rows; each row is distinct
  - Entries in columns are atomic
  - Entries from cloumns are from the same domain based on their data type including: 
   - number (numeric, integer, float, smallint,...)
   - character (string)
   - date 
   - logical (true or flase)
  - Operations combingin different data types are disallowed
  - Each attribute has a distinct name
  - The sequence of coluimns is insignificant
  - The sequence of rows is insignificant

## Non-relational Databases
- Examples of non-relational databases:
  - Document-oriented 
  - Graph based
  - Column based
  - Key-value
  - Hybrid
- No-SQL

## Query for Data
- There are ONLY FOUR BASIC commands for interacting with an SQL database. Can you figure out what they are?
- C.R.U.D - Create, Read, Update, Delete
- SELECT - to query data in the database
- INSERT - to insert data into a table
- UPDATE - to update data in a table
- DELETE - to delte data from a table

- SELECT
  - Ex: SELECT * FRP< dbo.Orders

  - EX: SELECT order_num.
               order_date.
               last_name FROM dbo.Orders
         Where last_name = 'Wright'
         
- INSERT
  -Ex: INSERT INTO dbo.Orders
    (order_id,
    first_name,
    last_name)
    
- VALUES
    (1234,
    ‘Cassie’,
    ‘Wright’)
    
- UPDATEEx: UPDATE dbo.Orders SET last_name = ‘Wright’
WHERE order_id = 1234
Ex: UPDATE dbo.Orders SET last_name = ‘Wright’
 WHAT WILL THIS DO??

- DELETE
Ex: DELETE FROM dbo.Orders
Ex: DELETE FROM dbo.Orders
WHERE last_name = ‘Wright’

# AWS Relational Database Service (RDS)

- A managed relational database service
- We can choose from:
- MySQL
- MariaDB
- Oracle
- MS SQL Server
- PostgreSQL
- Amazon Aurora

- Benefits:
- CPU, memory, storage, and IOPS can be scaled independently
- Backups, software patching, automatic failure detection, and recovery are all managed.
- Backups can be automated or manual.
- High availability with a primary instance and a synchronous secondary instance 
- We can use the database products we are already familiar with: MySQL, MariaDB, PostgreSQL, Oracle, Microsoft SQL Server.
- We can use AWS Identity and Access Management (IAM) to define users and permissions.
    
# Amazon DynamoDB
- Fully managed key-value and document NoSQL DB service
- AWS manages the underlying infrastructure
- Redundantly stores data across multiple facilities
- Core components:
  - Tables
  - Items
  - Attributes

# Amazon Redshift
- LARGE SCALE DATABASE service
- “Data Warehousing”
- Easily Scalable
- Compatible with familiar services (standard SQL)

# Amazon Aurora
- Relational DB service
- Compatible with MySQL and PostgreSQL
- ”Five times faster than standard MySQL”
- Highly Available; stores multiple copies of data across Availability Zones
