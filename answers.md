Database Management System (DBMS) Fundamentals
Components of a DBMS
A Database Management System (DBMS) consists of the following components:
Database Engine: Responsible for data storage, retrieval, and processing. It handles data manipulation operations like insert, update, delete, and retrieve.
Database Schema: Defines the logical structure of the database, including tables, fields, and relationships.
Query Processor: Interprets and executes database queries, typically written in SQL, to retrieve or modify data.
Transaction Management: Ensures database consistency and integrity by handling transactions, including rollback, commit, and concurrency control.
Data Dictionary: A metadata repository containing information about database schema, constraints, and data types.
User Interface: Provides tools or interfaces (e.g., GUI, CLI) for users to interact with the database.
Relational Database
A relational database organizes data into structured tables (relations) with rows and columns. It uses primary keys and foreign keys to establish relationships between tables.
Examples of Relational Databases:
MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Classifications of SQL
SQL is classified into three main categories:
Data Definition Language (DDL): Commands used to define and modify the database structure. Examples: CREATE, ALTER, DROP.
Data Manipulation Language (DML): Commands used to manage data within the database. Examples: SELECT, INSERT, UPDATE, DELETE.
Data Control Language (DCL): Commands used to control access and permissions in the database. Examples: GRANT, REVOKE.
Difference Between a Primary Key and a Foreign Key
The following table outlines the key differences between a Primary Key and a Foreign Key:
Aspect	Description
	
Primary Key	Uniquely identifies each record in a table. Cannot contain null values.
Foreign Key	References the primary key in another table and establishes a relationship.
Entity-Relationship Diagram (ERD)
An Entity-Relationship Diagram is a visual representation of the data model that describes the entities (objects) in the database, their attributes, and the relationships between them. It is widely used in database design to map the structure and interaction of entities.
Advantages of Relational Databases
Data Integrity: Maintains accuracy and consistency of data through constraints (e.g., primary keys).
Flexibility: Easily adapts to changing requirements by modifying the schema.
Data Security: Offers robust access control mechanisms.
Scalability: Supports large-scale data with efficient query processing.
Types of Data Types Used in Tables
Integer: Stores whole numbers.
Varchar/Char: Stores strings or text.
Date/Time: Stores date and time values.
Float/Decimal: Stores real numbers with fractional parts.
Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to provide a centralized, efficient, and secure platform for:
Storing and organizing data.
Facilitating easy data retrieval and manipulation using queries.
Ensuring data consistency, integrity, and security.
Supporting concurrent access by multiple users.
Automating data backup and recovery.
