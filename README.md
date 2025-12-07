📘 SQL University Project

This repository contains a university-level SQL assignment consisting of:

a full database schema & dataset (SQL_project.sql)

a Java GUI application packaged as a JAR (SQL_GUI.jar)

the project specifications and exercise description in PDF format
(SQL_PROJECT.pdf, 1η Ασκηση ΒΔ.pdf)

The project demonstrates database design, SQL querying, and interaction with a relational database through a graphical user interface.

🚀 Project Goal

The goal of this project is to:

Design and implement a relational database based on the requirements described in the PDFs.

Create and populate tables using SQL scripts.

Execute queries that satisfy the functional requirements of the assignment.

Provide a desktop interface (Java Swing application) that interacts with the database and performs:

Queries

Data retrieval

Inserts/updates (depending on assignment scope)

This project combines SQL skills with Java GUI programming, showing how applications interact with databases.

📂 Files Included
File	Description
SQL_project.sql	Full SQL script: schema creation + inserts
SQL_GUI.jar	Java desktop application to interact with the database
SQL_PROJECT.pdf	Main project description
1η Ασκηση ΒΔ.pdf	Assignment instructions (Greek)
🛠 Requirements

To run this project, you need:

✔ Java Runtime Environment (JRE)

Required to run the .jar GUI application.
Download: https://www.java.com/

✔ MySQL or MariaDB Server

You can use:

XAMPP MySQL

Standalone MySQL Server

MariaDB

✔ A SQL Client (optional but recommended)

Such as:

MySQL Workbench

phpMyAdmin

DBeaver

HeidiSQL

✔ Basic Web/Programming Technologies (used inside the project PDFs)

(Not required to run the project, but relevant to the assignment content)

SQL

Java

JDBC

Relational database concepts

📥 1. How to Clone the Repository

If you have Git installed, open a terminal and run:

git clone https://github.com/Zoubou/SQL-Uni-Project.git


🗄️ 2. How to Set Up the Database

Open MySQL Workbench or phpMyAdmin

Create a new database 

Import the SQL file:

MySQL Workbench

Server → Data Import → Import from Self-Contained File

Select: SQL_project.sql

Choose database

Run import

phpMyAdmin

Select database

Go to Import

Select: SQL_project.sql

Click Go

Your database is now created and populated.

▶️ 3. How to Run the GUI Application

Make sure MySQL is running

Open a terminal in the project folder

Run the JAR file:

java -jar SQL_GUI.jar


Inside the GUI:

Enter your MySQL login credentials

Select database

Start running queries through the interface

🎓 Summary

This project is a complete SQL + Java desktop application built for a university database course.
It includes:

Full relational database implementation

A complete GUI for interacting with the DB

Official project documentation

You can use it for learning SQL, practicing queries, or studying how Java applications connect to MySQL.
