Retail Sales & Customer Analytics Dashboard

📊 Project Overview

This project analyzes retail sales and customer transaction data to understand revenue performance, profitability, customer behaviour, product performance, sales channels, locations, and monthly sales trends.

The project was developed as a data analytics portfolio case study using Excel, Power Query, Power BI, and DAX.

The goal was to transform raw retail transaction data into an interactive dashboard that provides actionable business insights for decision-making.

⸻

🎯 Business Problem

A retail business needs to understand which products, locations, customer groups, and sales channels are driving revenue and profit.

The analysis focuses on identifying performance patterns and translating them into practical business recommendations.

⸻

❓ Business Questions

The analysis was designed to answer the following questions:

1. Which sales channel generates the highest revenue?
2. Which products generate the highest profit?
3. Which locations generate the highest revenue?
4. Which locations generate the highest profit?
5. Which products are best-selling based on quantity sold?
6. How does revenue change over time?
7. How profitable is the business overall?
8. What does customer purchasing behaviour reveal about repeat customers?

⸻

🗂️ Dataset

The dataset contains:

* 1,200 customers
* 27 products
* 8,500 orders
* 12 locations

Main tables

Table	Description
Customers	Customer demographics and registration information
Products	Product, category, brand and pricing information
Orders	Transaction-level sales data
Locations	City, state and regional information

⸻

🧹 Data Cleaning & Preparation

The dataset was reviewed and prepared before analysis.

Data-quality issues identified included:

* Inconsistent capitalization in city names
* Inconsistent capitalization in payment methods
* Leading whitespace in some sales-channel values

These issues were addressed during the data preparation process using Power Query.

⸻

🏗️ Data Modelling

A relational data model was created in Power BI using a star-schema approach.

The main relationships included:

* Customers → Orders
* Products → Orders
* Locations → Orders
* DateTable → Orders

The model allowed customer, product, geographic and time dimensions to filter transaction-level sales data.

⸻

🧮 DAX & KPI Development

Several DAX measures were created to support the analysis, including:

* Total Revenue
* Total Profit
* Total Cost
* Total Quantity
* Total Orders
* Total Customers
* Average Order Value
* Profit Margin %
* Revenue per Customer
* Average Orders per Customer
* Repeat Customers
* Repeat Customer Rate %
* Previous Month Revenue
* Revenue Growth %
* Revenue Share %

These measures were used to create the dashboard KPIs and analytical visuals.

⸻

📊 Dashboard

The Power BI report contains five analytical pages:

1. Executive Summary

Provides an overview of:

* Revenue
* Profit
* Orders
* Customers
* Average Order Value
* Profit Margin
* Monthly revenue trend
* Revenue by location
* Revenue by sales channel
* Top 5 products by profit

2. Profit Dashboard

Analyzes profitability across products, categories, regions and sales channels.

3. Revenue Dashboard

Examines revenue performance across products, locations, customer segments and sales channels.

4. Product Dashboard

Analyzes product revenue, profit, quantity sold and product profitability.

5. Customer Dashboard

Examines customer purchasing behaviour, repeat customers and customer-level performance.

⸻

🔍 Key Findings

💰 Overall Performance

The business generated approximately:

* ₦339M in total revenue
* ₦116M in total profit
* 34.23% profit margin
* 8,500 orders
* 1,200 customers
* ₦39.93K average order value

📍 Geographic Performance

Lagos Island generated the highest revenue among the locations shown in the Top 5 Cities analysis.

🛍️ Sales Channel Performance

Walk-in generated the highest revenue among the sales channels, followed by WhatsApp, Instagram and Website.

👗 Product Performance

Pleated Skirt was the highest-performing product by both revenue and profit.

The Top 5 Products by Profit included:

1. Pleated Skirt
2. Classic Shirt Dress
3. Wide-Leg Trousers
4. Classic Two-Piece
5. Casual Co-Ord Set

👥 Customer Behaviour

The analysis identified 1,191 repeat customers, representing a 99.25% repeat customer rate within this dataset.

Customers averaged approximately 7.08 orders per customer, while revenue per customer was approximately ₦282.82K.

📈 Revenue Trend

Monthly revenue showed a general upward trend across the analysis period, with fluctuations between individual months.

⸻

💡 Business Recommendations

Based on the analysis, the following actions are recommended:

* Prioritize inventory planning for high-performing products such as Pleated Skirt.
* Monitor high-profit products and consider maintaining sufficient stock to support continued demand.
* Strengthen the Walk-in and WhatsApp sales channels because they generated the strongest revenue performance.
* Continue monitoring customer purchasing behaviour and use repeat-customer insights to support retention strategies.
* Investigate high-performing locations such as Lagos Island for opportunities to increase sales and customer reach.
* Monitor monthly revenue trends to identify periods of stronger or weaker performance and improve planning.

⸻

🛠️ Tools & Skills Demonstrated

Tools:

* Microsoft Excel
* Power Query
* Power BI
* DAX

Skills:

* Data Cleaning
* Data Transformation
* Data Modelling
* Star Schema
* DAX Measures
* KPI Development
* Data Visualization
* Customer Analysis
* Product Analysis
* Sales Analysis
* Profitability Analysis
* Business Intelligence
* Business Recommendations

⸻

📁 Project Files

This repository contains:

* Case Study — detailed documentation of the project
* Dataset — supporting Excel dataset used for the analysis
* Power BI Dashboard — interactive .pbix report
* Dashboard Screenshots — visual evidence of the completed analysis

⸻

📸 Dashboard Preview

Executive Summary

Product Dashboard

Customer Dashboard

⸻

👩🏽‍💻 About the Project

This project was completed as part of my data analytics portfolio to demonstrate my ability to take a retail dataset from raw data through cleaning, modelling, analysis and visualization, and translate analytical findings into business recommendations.
