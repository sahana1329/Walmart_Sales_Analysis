# Walmart_Sales_Analysis
Walmart Sales Analysis using SQL and Python 

Project Overview

Retail companies generate large volumes of transaction-level data across branches, product categories, and payment methods. However, without structured analysis it can be difficult to understand what truly drives sales performance, profitability, and customer behavior.

In this project, I analyzed a Walmart retail dataset to uncover insights related to:

Sales performance across branches and product categories

Profitability patterns and margin differences

Customer purchasing behavior, including payment preferences and peak shopping hours

The goal was to simulate a real-world retail analytics scenario and demonstrate how data analysis can support better operational and business decisions.

Business Objectives

The analysis focused on answering key business questions:

Which branches and product categories generate the most sales?

Are high-sales categories also the most profitable?

What are the most preferred payment methods among customers?

When are the peak shopping hours during the day?

How do customer ratings and purchasing behavior vary across branches?

Project Workflow

Data Cleaning

Performed initial data exploration to ensure data quality.

Key steps included:

Inspecting column names and data types

Checking for missing values and duplicates

Validating numeric fields such as price and quantity

Standardizing date and time formats

Creating a cleaned dataset for reliable analysis

Tools used:

Python (Pandas)

Exploratory Data Analysis (EDA)

Used Python to explore trends and patterns within the data:

Sales distribution across branches and product categories

Customer payment preferences

Customer ratings across branches

Transaction frequency by time of day

Key techniques:

Pandas groupby aggregations

Distribution analysis

Time-based feature extraction

SQL Analysis

SQL-style aggregations were used to analyze key performance metrics:

Total sales by branch

Profitability by product category

Payment method usage

Customer rating patterns

Results were cross-validated with Python outputs to ensure accuracy and consistency.

Key Insights

Branch Performance

Certain branches contributed significantly more to total sales, indicating differences in location demand and customer traffic.

Product Category Profitability

High sales volume did not always translate to higher profit. Some lower-sales categories showed higher profit margins, highlighting opportunities for margin-focused strategies.

Payment Preferences

Customers showed a strong preference for digital and card payments, indicating the importance of efficient digital payment infrastructure.

Peak Shopping Hours

Transaction frequency analysis revealed specific peak shopping hours during the day, suggesting opportunities to optimize staffing and reduce checkout wait times.

Business Recommendations

Based on the analysis, retail managers could:

Focus inventory planning on high-margin product categories

Optimize staffing levels during peak shopping hours

Improve checkout efficiency by promoting digital payment methods

Analyze branch-level performance to tailor localized strategies

Tools & Technologies

Tool	Purpose

Python (Pandas) for	Data cleaning & analysis

SQL for	Aggregation and metric validation

Jupyter Notebook for	Analysis workflow

