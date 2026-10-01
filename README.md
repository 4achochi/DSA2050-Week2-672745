 # DSA 2050 Week 2 SQL Practical Lab

Name: Gregory Achochi
Student ID: 672745

# Objective

The objective of this practical was to acquire, inspect, integrate, and analyze retail customer and order data using Python, pandas, SQLite, SQL, and a JSON region lookup. The analysis focused on data grain, duplicate and unmatched keys, SQL filtering and aggregation, JOIN validation, sales reconciliation, customer-segment KPIs, and regional sales analysis.

# Key Findings

1. CustomerID C004 was duplicated in the customer dataset, causing the original JOIN to inflate the row count and sales total.
2. CustomerID C999 appeared in the orders dataset without a matching customer record.
3. After cleaning the duplicate key, the JOIN preserved the original order count and sales total.

# Files

* `DSA2050_Week2_SQL_Lab.ipynb` — completed analysis and SQL queries.
* `customers.csv` — customer source data.
* `orders.csv` — order transaction data.
* `regions.json` — region lookup data.
* `retail_lab.db` — local SQLite database, if included in the repository.
