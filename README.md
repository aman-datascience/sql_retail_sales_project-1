# SQL Retail Sales Analysis

## Project Overview

In this project, I analyzed retail sales data using SQL.

I created a table, checked the data, removed records with missing values, and then performed different SQL queries to answer business-related questions.

The main purpose of this project was to practice SQL and understand how SQL can be used to analyze sales data.

## Dataset

The dataset contains retail sales transaction details.

### Main Columns

| Column | Description |
|---|---|
| `transactions_id` | Unique transaction ID |
| `sale_date` | Date of the sale |
| `sale_time` | Time of the sale |
| `customer_id` | Customer ID |
| `gender` | Gender of the customer |
| `age` | Age of the customer |
| `category` | Product category |
| `quantiy` | Quantity of products sold |
| `price_per_unit` | Price of one unit |
| `cogs` | Cost of goods sold |
| `total_sale` | Total sale amount |

## Tools Used

- PostgreSQL
- SQL
- GitHub
- CSV Dataset

## Project Workflow

```text
Retail Sales Data
       ↓
Create Table
       ↓
Check Data
       ↓
Clean Data
       ↓
Analyze Data
       ↓
Answer Business Questions
```

## Data Cleaning

First, I checked the dataset for missing values.

I checked important columns such as transaction ID, sale date, sale time, gender, category, quantity, price, COGS, and total sales.

Records containing missing values were removed before performing the analysis.

## Data Exploration

I performed some basic checks to understand the dataset.

I found:

- Total number of records
- Total number of customers
- Number of unique customers
- Different product categories

## Business Questions

I used SQL to answer the following questions:

1. Find all sales made on `2022-11-05`.
2. Find Clothing transactions where quantity sold is greater than 3 in November 2022.
3. Calculate total sales and total orders for each category.
4. Find the average age of customers who purchased from the Beauty category.
5. Find transactions where total sales are greater than 1000.
6. Find the number of transactions by gender and category.
7. Find the best-selling month in each year based on average sales.
8. Find the top 5 customers based on total sales.
9. Find the number of unique customers in each category.
10. Divide orders into Morning, Afternoon, and Evening shifts.

## SQL Concepts Used

In this project, I used:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- COUNT()
- COUNT(DISTINCT)
- SUM()
- AVG()
- DISTINCT
- LIMIT
- CASE WHEN
- Date and Time Functions
- Subqueries
- CTE
- Window Functions
- RANK()
- PARTITION BY

## What I Learned

Through this project, I learned how to use SQL for real-world data analysis.

I practiced data cleaning, filtering, grouping, aggregation, date and time analysis, and window functions.

I also learned how to convert business questions into SQL queries.

## Files in This Repository

- `SQL - Retail Sales Analysis_utf.csv` - Dataset used for the project
- `sql_project_1.sql` - SQL queries used for the analysis
- `README.md` - Project information

## Future Improvements

I would like to extend this project by creating a Power BI dashboard and adding more sales and customer analysis.

## Author

**Aman Singh**

MSc Electronics | Data Science Learner

Currently learning:

- SQL
- Python
- Excel
- Power BI
- Data Analysis
- Generative AI
- Agentic AI
