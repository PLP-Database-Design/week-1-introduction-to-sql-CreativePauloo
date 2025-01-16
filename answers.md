Database Management System (DBMS) Fundamentals
Components of a DBMS
A Database Management System (DBMS) consists of the following components:
1. Database Engine: Responsible for data storage, retrieval, and processing. It handles data manipulation operations like insert, update, delete, and retrieve.
2. Database Schema: Defines the logical structure of the database, including tables, fields, and relationships.
3. Query Processor: Interprets and executes database queries, typically written in SQL, to retrieve or modify data.
4. Transaction Management: Ensures database consistency and integrity by handling transactions, including rollback, commit, and concurrency control.
5. Data Dictionary: A metadata repository containing information about database schema, constraints, and data types.
6. User Interface: Provides tools or interfaces (e.g., GUI, CLI) for users to interact with the database.

Relational Database
A relational database organizes data into structured tables (relations) with rows and columns. It uses primary keys and foreign keys to establish relationships between tables.
Examples of Relational Databases:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

Classifications of SQL
SQL is classified into three main categories:
1. Data Definition Language (DDL): Commands used to define and modify the database structure. Examples: CREATE, ALTER, DROP.
2. Data Manipulation Language (DML): Commands used to manage data within the database. Examples: SELECT, INSERT, UPDATE, DELETE.
3. Data Control Language (DCL): Commands used to control access and permissions in the database. Examples: GRANT, REVOKE.

Difference Between a Primary Key and a Foreign Key	
1. Primary Key Uniquely identifies each record in a table. Cannot contain null values.
2. Foreign Key References the primary key in another table and establishes a relationship.

Entity-Relationship Diagram (ERD)
An Entity-Relationship Diagram is a visual representation of the data model that describes the entities (objects) in the database, their attributes, and the relationships between them. It is widely used in database design to map the structure and interaction of entities.

Advantages of Relational Databases
1. Data Integrity: Maintains accuracy and consistency of data through constraints (e.g., primary keys).
2. Flexibility: Easily adapts to changing requirements by modifying the schema.
3. Data Security: Offers robust access control mechanisms.
4. Scalability: Supports large-scale data with efficient query processing.

Types of Data Types Used in Tables
1. Integer: Stores whole numbers.
2. Varchar/Char: Stores strings or text.
3. Date/Time: Stores date and time values.
4. Float/Decimal: Stores real numbers with fractional parts.

Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to provide a centralized, efficient, and secure platform for:
1. Storing and organizing data.
2. Facilitating easy data retrieval and manipulation using queries.
3. Ensuring data consistency, integrity, and security.
4. Supporting concurrent access by multiple users.
5. Automating data backup and recovery.
