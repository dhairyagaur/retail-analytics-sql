# Retail Analytics Using SQL

## Project Overview
This project focuses on analyzing a retail business dataset using SQL in PostgreSQL. The main objective is to answer business questions related to customers, products, orders, sales, and returns.

## Tools Used
- PostgreSQL
- pgAdmin 4
- SQL

## Database Tables
The project uses the following six tables:

- **Customers:** Customer details, city, and signup date.
- **Products:** Product names, categories, prices, and stock quantities.
- **Employees:** Employee details, branch city, and salary.
- **Orders:** Order dates, customers, employees, order status, and payment methods.
- **Order_Items:** Products sold, quantities, sale prices, and discount rates.
- **Returns:** Return dates and reasons for returned orders.

## SQL Concepts Used
The project includes 15 SQL queries covering:

- Filtering and sorting using `WHERE` and `ORDER BY`
- Joining multiple tables using `INNER JOIN` and `LEFT JOIN`
- Aggregate functions such as `SUM()`, `COUNT()`, and `AVG()`
- Grouping and filtering grouped results using `GROUP BY` and `HAVING`
- Subqueries and `NOT EXISTS`
- Date functions and `CASE` expressions
- Conditional aggregation
- Window functions and ranking
- Running totals
- Common Table Expressions (CTEs)
- Revenue calculations and customer analysis

## Business Analysis
The queries help analyze:

- Delivered orders within a specified date range
- Sales and net revenue by product category
- Customers with repeat purchases
- Customers without delivered orders
- Monthly sales trends and cumulative revenue
- Product stock levels and sales rankings
- Returned order values
- Top customers by net spending and their contribution to total delivered revenue

## Business Rules and Assumptions
- Gross item value is calculated as quantity multiplied by the sale-time unit price.
- Net revenue is calculated after applying the discount rate.
- Revenue calculations include only delivered orders unless a question specifies otherwise.
- Returned and cancelled orders are excluded from delivered revenue.
- Customers with no delivered orders are included where required.
- The average customer revenue in Question 14 is calculated across customers with delivered purchases.

For more details, see `Project_Assumptions.txt`.

## Project Files
- `Assignment_2_Queries.sql` — SQL queries used to answer the assignment questions.
- `Project_Assumptions.txt` — Business rules and assumptions used in the analysis.

## Conclusion
This project demonstrates how SQL can be used to analyze retail data, calculate sales performance, understand customer purchasing behaviour, and generate useful business insights.

