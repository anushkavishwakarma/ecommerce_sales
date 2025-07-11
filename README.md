# 🛒 E-Commerce Sales Database using SQL

This is a **SQL-only project** that simulates an e-commerce backend system. The database contains realistic, randomly generated data for customers, products, orders, and payments. It's ideal for learning and practicing SQL queries, understanding data relationships, and improving data analysis skills.

## 📁 Project Structure

The project includes the following files:
- `schema.sql` – SQL script to create all required tables
- `data.sql` – Sample data to populate the tables
- `queries.sql` – Collection of useful SQL queries for analysis

## 🔄 Table Overview

| Table Name   | Description                                 |
|--------------|---------------------------------------------|
| `customers`  | Contains customer details like name, email, addresss |
| `products`   | Product catalog including category, stock quantity and price |
| `orders`     | Stores order transactions by customer and date |
| `order_items`| Items per order with quantity and total price |
| `payments`   | Payment status and method for each order     |
| `shipping`   |Shipping status, carrier, and delivery date for each order   |

## 🔑 Key SQL Concepts Used

- `JOIN` operations (`INNER`, `LEFT`, `RIGHT`)
- `GROUP BY`, `ORDER BY`
- `Aggregate functions`: `SUM()`, `COUNT()`, `AVG()`
- `Subqueries` and `nested SELECT`
- `DATE` functions for time-based analysis
- Data filtering using `WHERE`, `HAVING`

---

## 💡 Sample Query Ideas

- List all customers who have placed at least one order. 
- Show total number of orders per customer.  
- List all orders along with the customer name and total amount.  
- Show the most popular product (by quantity sold).
- Display orders placed in the last 30 days.  


## 📊 Sample Output

Example:  ** List the names of customers who made payments over ₹3000.**

<img width="197" height="127" alt="image" src="https://github.com/user-attachments/assets/76f4cf66-a546-4ae2-b93e-9792c99ee49d" />


## ▶️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/anushkavishwakarma/ecommerce_sales.git

