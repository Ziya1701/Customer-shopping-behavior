# Customer Shopping Behavior Analysis
## Overview

This project analyzes customer shopping patterns using Python, MySQL, and Power BI.
The goal is to understand spending habits, product preferences, customer segments, subscription behavior, and discount usage.

A dataset of 3,900 records across 18 columns was used to generate insights that support strategic and marketing decisions.
<img width="1325" height="726" alt="Screenshot 2025-11-29 135036" src="https://github.com/user-attachments/assets/ecea46c6-67e0-4a30-9c29-89d3f08c0b70" />


## Dataset Summary
Total Rows: 3,900
Total Columns: 18
Contains:
Customer demographics
Purchase information
Product attributes
Behavior indicators like discounts, promo codes
Missing Values: 37 null values in review_rating

Data Set used :- 
<a href = https://github.com/Ziya1701/Customer-shopping-behavior/blob/main/customer_shopping_behavior.csv > Data set </a>

## Tools Used
Python: Pandas,
MySQL: Data storage & business queries and
Power BI: Dashboard development
## Steps Performed
### EDA in Python
Loaded data with Pandas
Checked structure (df.info())
Statistical summary (df.describe())
Identified missing values.

Jupyter File :- <a href = https://github.com/Ziya1701/Customer-shopping-behavior/blob/main/Customer_shopping_behavior.ipynb > Python </a>
### Data Cleaning
Filled missing review ratings using median rating per product category
Standardized column names to snake_case
Created:
age_group
purchase_frequency_days
Removed promo_code_used due to duplication
Uploaded cleaned data to MySQL

### SQL Business Insights
Queries were used to analyze:
Revenue by gender
High-value discount users
Top-rated products
Shipping type comparison
Subscriber vs non-subscriber revenue
Discount-driven products
Customer segmentation (New, Returning, Loyal)
Top 3 products per category
Repeat purchase vs subscription
Revenue by age group

## Power BI Dashboard
Dashboard includes:
Total customers
Average purchase amount
Average review rating
Revenue by category
Revenue and sales by age group
Subscription breakdown

## Business Recommendations
Increase subscription conversions
Strengthen loyalty programs
Optimize discount strategy
Promote top-rated products
Focus marketing on high-value age groups and express-shipping users




