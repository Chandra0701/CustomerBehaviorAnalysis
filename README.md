📊 Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using Python, PostgreSQL (SQL), and Power BI to uncover insights into spending patterns, product trends, customer demographics, and marketing opportunities. It includes full data cleaning, exploratory analysis, SQL-based business insights, and an interactive dashboard.

📁 Project Overview

The dataset consists of 3,900 transactional records containing customer demographics, product details, purchase behavior, and delivery preferences. The objective is to understand how customers shop, what they buy, how much they spend, and which factors influence their purchasing decisions.

This analysis supports business strategy in areas such as customer segmentation, product performance, subscription growth, and marketing optimization.

📦 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Product details: Item Purchased, Category, Size, Color

Purchase info: Purchase Amount, Season, Previous Purchases, Frequency

Behavior: Discount Applied, Promo Code Used, Review Rating

Shipping: Standard, Express, Next Day, Store Pickup

Missing Data:

37 values missing in Review Rating

🧹 Data Cleaning & Preparation (Python)

✔ Steps Performed

Loaded dataset using pandas

Standardized column names to snake_case

Imputed missing review ratings with median per category

Created new features:

age_group (binned ages)

purchase_frequency_days

Dropped redundant promo_code_used column

Verified consistency between discount and promotional features

Loaded cleaned DataFrame into PostgreSQL for SQL analysis

🧮 SQL-Based Business Analysis

Business questions and insights were developed using PostgreSQL

🔍 Key SQL Insights

Revenue by Gender – Compared purchase spending between genders

High-Spending Discount Users – Identified customers who used discounts yet spent above average

Top 5 Products by Rating

Shipping Type Comparison – Avg purchase amount for Standard vs Express

Subscribers vs Non-Subscribers – Avg spend + total revenue

Discount-Dependent Products – Items mostly purchased with discounts

Customer Segmentation – New, Returning, Loyal

Top 3 Products per Category – Based on purchase frequency

Repeat Buyers & Subscriptions – Are frequent buyers more likely to subscribe?

Revenue by Age Group – Contribution by Young Adult, Middle-aged, Adult, Senior

Screenshots and tables on pages 3–6 support these findings.

📊 Power BI Dashboard

A highly interactive dashboard was created to visualize insights, featuring:

Total number of customers

Average purchase amount

Average review rating

% of customers by subscription status

Revenue by category

Sales by category

Revenue & sales by age group

Filters: Gender, Category, Shipping Type, Subscription, Season

The dashboard provides stakeholders with real-time analysis for data-driven decisions.

💡 Business Recommendations

✔ Boost Subscriptions

Promote exclusive membership benefits to increase subscriber count.

✔ Strengthen Loyalty Programs

Reward repeat buyers and incentivize movement into the “Loyal” segment.

✔ Review Discount Strategy

Balance discounts with profit margins to ensure sustainable revenue.

✔ Improve Product Positioning

Highlight top-rated or frequently purchased products in marketing campaigns.

✔ Targeted Marketing

Focus ads and offers on:

High-revenue age groups

Express-shipping customers

Categories with strong performance

🛠 Tools & Technologies
Category	Tools
Programming	Python (Pandas, NumPy)
Visualization	Power BI
Database	PostgreSQL
Analysis	SQL, EDA
Version Control	Git & GitHub
