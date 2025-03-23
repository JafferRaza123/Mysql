# SQL Database Operations

This repository contains SQL queries for creating, managing, and manipulating databases and tables.

## 📜 Operations Performed

1️⃣ **Database Creation and Deletion**
```sql
CREATE DATABASE temp1;
CREATE DATABASE temp2;
CREATE DATABASE Jaf;
DROP DATABASE temp1;
DROP DATABASE temp2;
2️⃣ Creating and Using the college Database
CREATE DATABASE college;
USE college;
3️⃣ Creating a Table (student)
CREATE TABLE student (
    ID INT PRIMARY KEY,
    Name VARCHAR(50),
    Age INT NOT NULL
);
4️⃣ Inserting Data into student Table
INSERT INTO student VALUES (1, "Jaffer", 26);
INSERT INTO student VALUES (2, "Mahnoor", 27);
INSERT INTO student VALUES (3, "Hoor Dhakan", 18);
5️⃣ Retrieving Data
SELECT * FROM student;
6️⃣ Checking Database and Table Existence
CREATE DATABASE IF NOT EXISTS college;
SHOW DATABASES;
SHOW TABLES;
7️⃣ Dropping a Table
DROP TABLE college;
📌 Working with the Jaf Database
USE jaf;
Creating a Student Table
CREATE TABLE Student (
    ROLLNUM INT PRIMARY KEY,
    Name VARCHAR(50)
);
Inserting Data
INSERT INTO student (ROLLNUM, Name) VALUES
(104, "Jaffer"),
(105, "Mahfer");
Retrieving Data
SELECT * FROM student;
Adding More Records
INSERT INTO student VALUES (106, "Hoor Dhakan");
SELECT * FROM student;
