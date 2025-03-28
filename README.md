# Online Bookstore SQL Project

## 📌 Project Overview
This project is a SQL-based Online Bookstore that efficiently manages books, customers, and orders. It demonstrates the use of relational databases, SQL queries, and advanced querying techniques to extract meaningful insights from the data.

## 🚀 Features Implemented
- **Database Management**: Created and managed a structured database with multiple tables.
- **Data Querying**: Implemented SQL queries to extract, filter, and analyze data.
- **Advanced SQL Techniques**: Used JOINS, Aggregations, CTEs, Window Functions, and Subqueries.
- **Data Importing**: Imported data into tables using the `COPY` command.


## 🗂 Database Schema
The project consists of the following tables:
1. **Books** - Stores book details like title, author, genre, published year, price, and stock.
2. **Customers** - Contains customer details such as name, email, phone, city, and country.
3. **Orders** - Maintains order details including order ID, customer ID, book ID, order date, quantity, and total amount.

## 📊 SQL Queries Used
### 🔍 Basic Queries
- Retrieve all books in a specific genre.
- Find books published after a certain year.
- List customers from a specific country.
- Retrieve orders placed within a date range.
- Calculate total stock of available books.
- Find the most expensive book.

### 📈 Advanced Queries
- Retrieve the total number of books sold per genre.
- Calculate the average price of books in a specific genre.
- Identify customers who have placed at least 2 orders.
- Find the most frequently ordered book.
- Calculate total revenue from all orders.

## 🛠 Technologies Used
- **Database**: SQL
- **SQL Concepts**: JOINS, Aggregations, CTEs, Window Functions, Subqueries

## 📂 Project Setup
1. **Create Database**: `CREATE DATABASE OnlineBookstore;`
2. **Switch to Database**: `\c OnlineBookstore;`
3. **Run SQL Scripts**: Execute the table creation and query scripts.
4. **Import Data**: Use `COPY` commands to import data from CSV files.

## 📌 Key Takeaways
- Designed a fully functional relational database.
- Practiced writing optimized SQL queries for real-world scenarios.
- Gained experience in data analysis using SQL.


