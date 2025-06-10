# -SQLBolt-Movie-Database-using-MySQL

# 🐬 Learn SQL with MySQL – Beginner Project

Welcome to the **Learn SQL with MySQL** project! This repository is designed to help beginners understand the fundamentals of SQL through simple, interactive-style exercises and real-world examples using the MySQL database engine.

---

## 📌 About the Project

This project is inspired by platforms like **SQLBolt**, offering a hands-on approach to learning SQL. It includes structured lessons, example queries, and practice exercises that cover the basics of SQL syntax and logic.

---

## 🎯 Project Goals

- ✅ Learn how to write basic `SELECT` queries
- ✅ Understand how to filter, sort, and group data
- ✅ Practice joining multiple tables
- ✅ Explore data transformation using SQL functions
- ✅ Build confidence in querying relational databases

---

## 🧠 Key Concepts Covered

- `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `GROUP BY`
- Aggregate functions: `COUNT()`, `SUM()`, `AVG()`, `MAX()`, `MIN()`
- Table joins: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
- Subqueries and nested queries
- Data types and table structure

---

## 📁 Repository Structure
- SQL Queries: This section contains SQL queries used for data extraction, transformation, and analysis.
- Documentation: The documentation offers detailed explanations of the data analysis process and showcases the insights we've uncovered.
- Data: Access the dataset used for analysis, as well as any cleaned or transformed data, in this section.

## Example Queries
Example Queries
SELECT DISTINCT director FROM movies
ORDER BY director ASC;

<img width="291" alt="image" src="https://github.com/user-attachments/assets/853b8909-4227-4dfd-ba8c-db6a491c06cf" />


SELECT title, year FROM movies ORDER BY year DESC LIMIT 4;

<img width="518" alt="image" src="https://github.com/user-attachments/assets/45a2b27f-4d7d-482f-ab17-38da8848e6d1" />


SELECT title FROM movies ORDER BY title ASC
LIMIT 5 OFFSET 5;

<img width="337" alt="image" src="https://github.com/user-attachments/assets/2c7a6be5-f2ef-4366-8e9e-82fa1a47249f" />


SELECT city, population FROM north_american_cities
WHERE country LIKE "Mexico" ORDER BY population DESC
LIMIT 2;

<img width="507" alt="image" src="https://github.com/user-attachments/assets/bd8522f0-4544-435d-ae04-a7d6f542356e" />


