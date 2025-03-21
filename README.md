# 📝 Assignment: Introduction to Databases

## 🎯 Learning Objectives  
- Understand how to create and manage databases in SQL.  
- Learn how to use SQL commands to create and delete databases.  
- Gain experience working with basic SQL commands for database management.

---

## 📋 What You'll Need  
💻 A computer with internet access and a database setup (e.g., MySQL, PostgreSQL, etc.).  
📝 A text editor (e.g., Visual Studio Code, Sublime Text, or any SQL editor).  
📚 Basic knowledge of SQL queries and database management.

---

## 📝 Submission Instructions  
📂 Write all your SQL queries in **answers.sql** file.  
✍️ Answer each question concisely and make sure your queries are clear and correct.  
🗣️ Structure your responses clearly, and use comments if necessary to explain your approach.

---

## 📚 Assignment Questions  
 1. Write an SQL query to create a new database called **salesDB**.  
 2. Write an SQL query to drop (delete) the database called **demo**.  

---

Good luck 🚀


## Steps taken 
Step 1: Set Up Your Project Locally
Create a new folder for the assignment:


mkdir sql-assignment

cd sql-assignment

Create a file named answers.sql:

crete a file called ansewers.sql

Step 2: Write Your SQL Queries

Open answers.sql in a text editor (VS Code, Sublime Text, etc.) and write the answers:


-- 1. Create a new database called salesDB
CREATE DATABASE salesDB;

-- 2. Drop (delete) the database called demo
DROP DATABASE demo;
Save the file.

Step 3: Initialize Git and Push to GitHub
Initialize a Git repository:


git init

Add a .gitignore file (optional but recommended):


echo "*.log" >> .gitignore

Stage the file:


git add answers.sql

Commit your changes:


git commit -m "Added SQL queries for database creation and deletion"

Create a new GitHub repository:

Go to GitHub

Click New Repository

Name it something like sql-assignment

Click Create Repository

Link your local repository to GitHub:


git remote add origin https://github.com/Dorothy2020/sql-assignment.git

Push your work to GitHub:


git branch -M main

git push -u origin main

