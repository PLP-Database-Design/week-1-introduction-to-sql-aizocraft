# Assignment Week 1

## 1. State and Explain the components of a DBMS (Database Management System)
A DBMS consists of the following components:
- **Hardware**: Physical devices such as servers and storage that store and process the database.
- **Software**: The DBMS itself that provides an interface to interact with the database.
- **Data**: Organized collection of data that the DBMS manages.
- **Users**: Includes database administrators, developers, and end-users who interact with the system.
- **Procedures**: Documented processes for setting up and maintaining the database system.

## 2. What is a relational database? Give 4 examples.
A relational database organizes data into structured tables (relations) with rows and columns. Each row represents a record, and each column represents an attribute.
Examples:
1. MySQL
2. PostgreSQL
3. Microsoft SQL Server
4. Oracle Database

## 3. State and Explain three classifications of SQL
- **DDL (Data Definition Language)**: Used to define and modify database structures (e.g., `CREATE`, `ALTER`, `DROP`).
- **DML (Data Manipulation Language)**: Used for managing data within tables (e.g., `INSERT`, `UPDATE`, `DELETE`).
- **DCL (Data Control Language)**: Used for controlling access to data (e.g., `GRANT`, `REVOKE`).

## 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for a record in a table. It ensures no duplicate values and cannot be null.
- **Foreign Key**: A field in one table that links to the primary key of another table, ensuring referential integrity between tables.

## 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of entities, their attributes, and relationships in a database. It helps in designing and understanding database structures.

## 6. What are the advantages of relational databases?
- **Data Integrity**: Ensures accuracy and consistency of data.
- **Flexibility**: Easy to add, update, or delete data without affecting other components.
- **Data Security**: Provides robust mechanisms for access control and user permissions.
- **Query Capabilities**: Supports complex queries using SQL for data retrieval.

## 7. State four types of data types used to store data in tables
1. **INTEGER**: For storing whole numbers.
2. **VARCHAR**: For storing variable-length text.
3. **DATE**: For storing date values.
4. **DECIMAL**: For storing precise numeric values, such as financial data.

## 8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to provide an efficient, reliable, and secure platform for storing, retrieving, and managing data. It facilitates data sharing, supports data integrity, and ensures consistency across applications.
