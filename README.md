
Task 6: Sales Trend Analysis Using Aggregations
 Objective

The goal of this task is to analyze monthly revenue and order volume from the online_sales dataset. By using SQL aggregations, we aim to identify sales trends over time and answer common interview-style questions about data grouping, aggregation, and sorting.

🛠 Tools Used

Database: PostgreSQL / MySQL / SQLite (any one can be used)

Language: SQL

 Dataset

Table: orders

order_id – Unique identifier for each order

order_date – Date of the order

amount – Revenue generated from the order

product_id – Product identifier

 Approach

Extract month and year from order_date using EXTRACT() or database-specific functions.

Group data by year and month to calculate aggregates.

Aggregate functions used:

SUM(amount) → monthly revenue

COUNT(DISTINCT order_id) → order volume

Sort results by year and month to observe trends.

Apply filtering (WHERE + LIMIT) for specific periods or top-performing months.
