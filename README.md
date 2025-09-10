🍕 Pizza Sales Analysis – SQL Project

This project uses MySQL to create and analyze a Pizza Hut sales database. It demonstrates SQL concepts such as database creation, table design, joins, aggregations, window functions, and analytical queries.

📂 Database Structure

Database: pizzahut

Tables:

orders → stores order ID, order date, and time.

order_details → stores details of each order (pizza, quantity).

pizzas → contains information about pizza size, type, and price.

pizza_types → contains pizza category and name.

🔎 Queries Covered

The project includes basic, intermediate, and advanced SQL queries:

✅ Basic Queries

Count total number of orders placed.

Calculate total revenue from pizza sales.

Find the highest-priced pizza.

Identify the most common pizza size ordered.

List top 5 most ordered pizza types by quantity.

🟡 Intermediate Queries

Find total quantity of pizzas sold by category.

Distribution of orders by hour of the day.

Category-wise distribution of pizzas.

Average number of pizzas ordered per day.

Top 3 pizzas based on revenue.

🔥 Advanced Queries

Revenue contribution (%) of each pizza category.

Cumulative revenue generated over time.

Top 3 pizzas by revenue within each category (using RANK() window function).

🛠 SQL Concepts Used

DDL (CREATE TABLE)

DML (SELECT, JOIN, GROUP BY, ORDER BY, LIMIT)

Aggregate functions → SUM(), COUNT(), AVG(), ROUND()

Date/Time functions → HOUR()

Window functions → RANK(), cumulative SUM() OVER()

Subqueries (inline views for average orders and percentage revenue)

🎯 Learning Outcomes

Understand relational database design.

Perform data analysis in SQL.

Apply window functions for advanced insights.

Practice real-world business queries like sales tracking, product performance, and revenue analysis.
