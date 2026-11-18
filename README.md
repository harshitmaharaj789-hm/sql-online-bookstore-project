# 📚 Online Bookstore Data Analysis using PostgreSQL

## 📌 Project Overview

This project focuses on analyzing an Online Bookstore database using PostgreSQL. The objective is to explore book sales, customer information, order details, revenue, and inventory through SQL queries.

The project includes basic and advanced SQL queries to extract meaningful insights from the database.

## 🎯 Project Objectives

- Analyze book inventory and pricing.
- Identify customer purchasing patterns.
- Calculate total revenue generated from orders.
- Analyze book sales by genre and author.
- Identify top-selling and most expensive books.
- Calculate remaining stock after fulfilling orders.

## 🗄️ Database Structure

The project consists of three relational tables:

| Table | Description |
|---|---|
| Books | Contains book details, genre, author, price, and stock. |
| Customers | Contains customer information, including name, email, city, and country. |
| Orders | Contains order details, customer IDs, book IDs, quantity, and total amount. |

### Database Relationships

- Books → Book_ID
- Customers → Customer_ID
- Orders → Book_ID and Customer_ID

## 🛠️ Tools & Technologies

- PostgreSQL
- pgAdmin 4
- SQL

## 📊 SQL Concepts Used

- Database and Table Creation
- SELECT and WHERE
- ORDER BY and LIMIT
- DISTINCT
- Aggregate Functions (SUM, AVG, COUNT)
- GROUP BY and HAVING
- JOIN
- BETWEEN
- COALESCE

## 🔍 Project Analysis

### Basic SQL Queries
- Retrieve books by genre.
- Find books published after 1950.
- Identify customers from Canada.
- Retrieve orders placed in November 2023.
- Calculate total available stock.
- Find the most expensive and lowest-stock books.
- Calculate total revenue.

### Advanced SQL Queries
- Calculate books sold by genre.
- Find average book prices by genre.
- Identify customers with at least two orders.
- Find the most frequently ordered book.
- Identify the top-priced Fantasy books.
- Analyze book sales by author.
- Identify cities of customers spending over $30.
- Find the highest-spending customer.
- Calculate remaining book inventory.

## 📁 Project Files

- `Online_Bookstore_SQL_Queries.sql` – SQL queries and database operations.
- `SQL_Project_Requirements.pdf` – Project questions and requirements.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Working with relational databases.
- Writing SQL queries for data analysis.
- Using aggregate functions and joins.
- Analyzing customer orders and sales.
- Extracting meaningful insights from structured data.

---

**Project Type:** SQL Data Analysis Project  
**Database:** PostgreSQL  
**Created by:** Harshit Maharaj
