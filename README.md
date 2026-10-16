
# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes retail customer shopping data using Python, PostgreSQL, and Power BI to understand purchasing patterns, product preferences, customer segments, and subscription behavior.

## Objectives
- Analyze customer purchasing patterns and demographics.
- Compare revenue across customer groups and age groups.
- Understand discount usage and product ratings.
- Examine subscription behavior and customer loyalty.
- Present insights through an interactive Power BI dashboard.

## Tools & Technologies
- **Python:** Pandas, data cleaning, exploratory data analysis
- **SQL:** PostgreSQL, aggregations, subqueries, CTEs, window functions
- **Power BI:** Interactive dashboards and data visualization

## Dataset
- **Records:** 3,900
- **Columns:** 18
- **Data includes:** Customer demographics, purchase amounts, product categories, discounts, review ratings, shipping types, and subscription status.

## Project Workflow

### 1. Python — Data Preparation
- Loaded and explored the customer shopping dataset.
- Checked missing values and data types.
- Imputed missing review ratings using category-wise median values.
- Created age-group and purchase-frequency features.
- Prepared the cleaned data for SQL analysis.

### 2. PostgreSQL — SQL Analysis
Used SQL queries to answer 10 business questions:
1. Revenue by gender.
2. Customers using discounts while spending above average.
3. Top five products by average review rating.
4. Average purchase amount by shipping type.
5. Spending and revenue by subscription status.
6. Products with the highest discount rates.
7. New, returning, and loyal customer segmentation.
8. Top three products within each category.
9. Subscription status among repeat buyers.
10. Revenue contribution by age group.

### 3. Power BI — Dashboard
Created an interactive dashboard to explore:
- Customer count and average purchase amount.
- Average review rating.
- Subscription distribution.
- Revenue by product category and age group.
- Customer behavior across demographic and purchasing groups.

## Repository Structure

- `data/` — Customer shopping dataset
- `python/` — Python analysis notebook
- `sql/` — SQL business analysis queries
- `powerbi/` — Power BI dashboard

## How to Use
1. Download or clone this repository.
2. Open the Python notebook in Jupyter Notebook or Google Colab.
3. Update the dataset path if needed and run the notebook.
4. Load the prepared data into PostgreSQL and execute the SQL queries.
5. Open the Power BI dashboard in Power BI Desktop.

## Attribution
This portfolio project is based on the customer shopping behavior analysis project by Amlan Mohanty.

Original repository:
https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI

Please refer to the original repository for licensing and attribution requirements.

## Disclaimer
This project is intended for learning and portfolio demonstration. Findings describe the provided dataset and do not establish causal relationships.
