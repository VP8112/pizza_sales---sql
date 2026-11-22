# Pizza Sales Analysis Using SQL

## About the Project

This project focuses on analyzing pizza sales data using **SQL (MySQL)** to identify sales trends, product performance, category-wise contributions, and customer ordering patterns.

The analysis uses SQL queries to extract meaningful business insights related to revenue generation, popular pizza types, ordering frequency, and peak sales periods. The project aims to demonstrate how SQL can support data-driven decision-making in sales, category management, and demand planning.

---

## Project Objectives

The main objectives of this project are:

- Analyze overall sales performance and revenue generation.
- Identify the most popular and highest-revenue-generating pizza types.
- Evaluate category-wise sales and revenue contributions.
- Understand customer ordering patterns across different hours of the day.
- Calculate average daily pizza demand.
- Identify top-performing products within each category.

---

## Dataset

**Dataset:** Pizza Sales Dataset

The dataset contains transactional sales information, including order details, pizza types, categories, prices, quantities, and order dates and times.

### Tables Used

| Table | Description |
|---|---|
| orders | Contains order IDs, dates, and order times. |
| order_details | Contains order details, pizza IDs, and quantities. |
| pizzas | Contains pizza IDs, sizes, and prices. |
| pizza_types | Contains pizza names, categories, and ingredients. |

---

## Tools and Technologies

- MySQL
- MySQL Workbench
- SQL

---

## SQL Concepts Applied

- SELECT, WHERE, ORDER BY and GROUP BY
- Aggregate Functions (SUM, COUNT, AVG)
- Joins (INNER JOIN)
- Subqueries
- Window Functions (RANK)
- Date and Time Functions
- LIMIT and ROUND

---

## Key Analysis Performed

### 1. Sales Performance Analysis
- Calculated the total number of orders placed.
- Evaluated total revenue generated from pizza sales.
- Identified the highest-priced pizza.

### 2. Product Performance Analysis
- Identified the most frequently ordered pizza size.
- Ranked the top five most-ordered pizza types.
- Identified the top three revenue-generating pizza types.

### 3. Category Management
- Analyzed total pizza quantities across different categories.
- Evaluated category-wise product distribution.
- Calculated the percentage contribution of each category to total revenue.
- Identified the top three revenue-generating pizzas within each category.

### 4. Demand Management
- Analyzed hourly order distribution to identify peak ordering periods.
- Calculated average daily pizza orders.
- Evaluated ordering frequency to understand demand patterns.

---

## Key Findings

The analysis generated the following insights:

- **Total Orders:** 21,350 orders.
- **Total Revenue:** $817,860.05.
- **Highest-Priced Pizza:** The Greek Pizza ($35.95).
- **Most Popular Category:** Classic, with 14,888 pizzas ordered.
- **Top Revenue-Generating Pizza:** The Thai Chicken Pizza ($43,434.25).
- **Average Daily Demand:** 138 pizzas.
- **Peak Ordering Periods:** 12 PM–1 PM and 5 PM–7 PM.
- **Highest Category Revenue Contribution:** Classic category (26.91%).

---

## Business Applications

The analysis provides insights that can support:

- **Sales Optimization:** Identifying high-revenue products and sales trends.
- **Category Management:** Evaluating category performance and product contribution.
- **Demand Planning:** Understanding peak ordering periods and daily demand patterns.
- **Product Strategy:** Identifying popular products and prioritizing high-performing categories.

---

## Conclusion

This project demonstrates the application of SQL in business-oriented data analysis. By analyzing transactional sales data, it identifies important revenue drivers, product performance trends, category contributions, and customer ordering patterns.

The findings highlight how structured data analysis can support informed decisions in sales optimization, category management, and demand planning.

---

## Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab, India
