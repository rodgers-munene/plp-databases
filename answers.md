# Database Management Systems (DBMS)
1. Software: The computer programs that manage the database, including the DBMS itself and supporting software. 
2. Hardware: The physical infrastructure, such as computers, storage devices, and other electronic components. 
3. Data: The raw facts or numbers stored in the database.

## 2. What is a Relational Database?
A relational database is a type of database that stores data in tables with rows and columns. Each table represents a different entity, and relationships between tables are established through keys.

### Examples:
1. **MySQL**
2. **PostgreSQL**
3. **SQLite**
4. **Microsoft SQL Server**

## 3. Classifications of SQL
SQL (Structured Query Language) is classified into three main categories:

### a. **Data Definition Language (DDL)**
- Used to define and manage database structures.
- Commands: `CREATE`, `ALTER`, `DROP`

### b. **Data Manipulation Language (DML)**
- Used to manipulate data within existing structures.
- Commands: `INSERT`, `UPDATE`, `DELETE`, `SELECT`

### c. **Data Control Language (DCL)**
- Used to control access to data within the database.
- Commands: `GRANT`, `REVOKE`

## 4. Primary Key vs. Foreign Key
### **Primary Key**
- Uniquely identifies each record in a table.
- Cannot contain NULL values.
- Each table can have only one primary key.

### **Foreign Key**
- Establishes a link between two tables.
- Refers to the primary key of another table.
- Can contain duplicate values and NULL values.

## 5. Entity-Relationship Diagram (ERD)
An Entity-Relationship Diagram (ERD) is a visual representation of the entities and relationships within a database. It helps in designing and understanding the database structure by showing entities, attributes, and the relationships between them.

## 6. Advantages of Relational Databases
- **Data Integrity**: Maintains accuracy and consistency of data.
- **Flexibility**: Easily accommodates changes in data structure.
- **Security**: Provides mechanisms to protect data from unauthorized access.
- **Support for SQL**: Utilizes SQL for querying and managing data efficiently.

## 7. Four Types of Data Types Used in Tables
1. **Integer**: Used for whole numbers.
2. **Varchar**: Used for variable-length strings.
3. **Date**: Used for storing dates.
4. **Boolean**: Used for true/false values.

## 8. Purpose of a Database Management System (DBMS)
The primary purpose of a DBMS is to provide a systematic and organized way to store, retrieve, and manage data. It ensures data integrity, security, and efficient access while supporting multiple users and applications simultaneously.
