# 🛒 E-Commerce Sales SQL Project

A complete end-to-end **SQL analytics project** built using **MySQL**.  
This project demonstrates the ability to design, populate, and analyze a relational database for a sample e-commerce business.

---

## 📘 Overview

This project models a sample e-commerce platform and performs detailed data analysis using SQL.  
It showcases SQL proficiency — from database creation to advanced analytical queries involving **joins, subqueries, aggregations, and set operations**.

---

## 🧩 Database Design

The database consists of **6 interconnected tables** designed to represent a simple e-commerce ecosystem:

| Table | Description |
|--------|-------------|
| `customers` | Stores customer information |
| `products` | Product catalog details |
| `orders` | Order header details linked to customers |
| `order_items` | Junction table connecting orders and products |
| `payments` | Stores transaction data linked to orders |
| `product_reviews` | Stores customer reviews and ratings for products |

📈 **ER Diagram:**  
The database schema is visualized in `er_diagram.png` (and designed using `workbench_model.mwb`).

---

## ⚙️ How to Run the Project

1. **Set Up the Database**
   - Open MySQL Workbench (or any MySQL environment).
   - Execute the file `1_schema_and_data.sql`.
   - This script will:
     - Create the database `prakash`.
     - Create all 6 tables with proper constraints and relationships.
     - Insert all sample data (30 customers, 50 products, 400 orders, etc.).

2. **Run the Analytical Queries**
   - Open `2_analysis_queries.sql`.
   - Execute the queries one by one to explore business insights.
   - Queries are organized from basic to advanced levels.

---

## 📂 Project Files

| File Name | Description |
|------------|-------------|
| `1_schema_and_data.sql` | DDL + DML scripts to create and populate the database |
| `2_analysis_queries.sql` | 30+ analytical queries across six difficulty levels |
| `er_diagram.png` | Entity Relationship (ER) diagram of the database |
| `workbench_model.mwb` | MySQL Workbench model file |

---

## 📊 Query Levels

| Level | Topics Covered |
|-------|----------------|
| **Level 1** | Basic SELECT, WHERE, ORDER BY |
| **Level 2** | Filtering using LIKE, IN, BETWEEN, IS NULL |
| **Level 3** | Aggregations using COUNT, SUM, AVG, GROUP BY |
| **Level 4** | Multi-table JOINs (INNER, LEFT JOIN) |
| **Level 5** | Subqueries (scalar, correlated, column) |
| **Level 6** | Set operations (UNION, EXISTS) |

---

## 🎯 Key Highlights

- Designed a **normalized relational database schema** with proper keys and constraints.  
- Created **synthetic sample data** for realistic analysis.  
- Wrote **30+ analytical SQL queries** to answer business questions.  
- Developed an **ER diagram** and **Workbench model** for visual understanding.  
- Demonstrated SQL skills across multiple complexity levels.

---

## 💡 Skills Demonstrated

- SQL Database Design (DDL & DML)
- Data Analysis and Aggregation
- Complex Joins and Subqueries
- Query Optimization
- Real-world E-commerce Data Modeling

---

## 🧠 Example Business Questions Answered

- Which customers placed the highest number of orders?  
- What are the top-selling products by category?  
- Which products have the highest average review rating?  
- What is the total revenue generated per month?  
- Which customers both ordered and reviewed products?

---

## 📈 ER Diagram

![E-Commerce Database ER Diagram](er_diagram.png)

---

## 🏁 Conclusion

This project demonstrates a complete workflow — from **database design and population** to **data-driven analysis using SQL**.  
It’s ideal for showcasing SQL proficiency in **data analytics**, **business intelligence**, and **database development**.

---

**📍 Author:** B. Vedhaprakash  
**🔗 Tools Used:** MySQL Workbench, SQL Scripts, ER Modeling  
**📅 Year:** 2025
