# Sales-Data-Analysis

# About

We are analyzing sales data to identify high-performing branches and products, analyze sales patterns of various products, and understand customer behavior. The primary objective is to enhance and optimize sales strategies. The dataset utilized in this project is sourced from the Kaggle Sales Forecasting Competition.

# Purposes of the Project

The main goal of this project is to gain insights from sales data, exploring the various factors that influence sales across different branches.

# About Data

This project's data was obtained from the Kaggle Sales Forecasting Competition and it encompasses sales transactions from three branches situated in different cities: Mandalay, Yangon, and Naypyitaw. The dataset contains 17 columns and 1000 rows:

Column	Description	Data Type
invoice_id	Invoice of the sales made	VARCHAR(30)
branch	Branch at which sales were made	VARCHAR(5)
city	The location of the branch	VARCHAR(30)
customer_type	The type of the customer	VARCHAR(30)
gender	Gender of the customer making purchase	VARCHAR(10)
product_line	Product line of the product sold	VARCHAR(100)
unit_price	The price of each product	DECIMAL(10, 2)
quantity	The amount of the product sold	INT
VAT	The amount of tax on the purchase	FLOAT(6, 4)
total	The total cost of the purchase	DECIMAL(12, 4)
date	The date on which the purchase was made	DATETIME
time	The time at which the purchase was made	TIME
payment	The total amount paid	DECIMAL(10, 2)
cogs	Cost Of Goods sold	DECIMAL(10, 2)
gross_margin_pct	Gross margin percentage	FLOAT(11, 9)
gross_income	Gross Income	DECIMAL(12, 4)
rating	Rating	FLOAT(2, 1)

# Analysis List:

# 1. Product Analysis

Analyze different product lines.

Identify top-performing product lines.

Find areas for improvement.

# 2. Sales Analysis

Understand sales trends.

Evaluate the effectiveness of sales strategies.

Optimize modifications to increase revenue.

# 3. Customer Analysis

Identify customer segments.

Analyze purchasing trends.

Evaluate profitability per customer segment.

# Approach Used

# 1. Data Wrangling

Detect missing values and handle them effectively.

Build a database and clean data for accuracy.

Ensure no NULL values exist in the dataset.

# 2. Feature Engineering

Time of Day Column: Categorize sales into Morning, Afternoon, and Evening.

Day Name Column: Extract weekday names for sales trend analysis.

Month Name Column: Identify monthly sales trends.

# 3. Exploratory Data Analysis (EDA)

Address business objectives using statistical and visual analysis.

# Business Questions Answered

# Generic Questions

- How many distinct cities are present in the dataset?

- In which city is each branch situated?

# Product Analysis

- How many distinct product lines are there?

- What is the most common payment method?

- What is the best-selling product line?

- What is the total revenue by month?

- Which product line generates the highest revenue?

- Which branch sells the most?

- What is the most common product line by gender?

- What is the average rating of each product line?

# Sales Analysis

- Sales performance across different times of the day.

- Identify customer types that generate the most revenue.

- Which city has the highest VAT percentage?

- Which customer type pays the most VAT?

# Customer Analysis

- How many unique customer types exist?

- How many unique payment methods exist?

- Which customer type buys the most?

- What is the gender of most customers?

- What is the gender distribution per branch?

- When do customers give the most ratings?

- Which days receive the best average ratings?

# Power BI Implementation

Power BI played a crucial role in visualizing sales data efficiently. With its easy-to-use interface and powerful visualization tools, we were able to create interactive dashboards that provide deep insights into sales trends, customer behavior, and product performance.

# Key Power BI Features Used:

# Data Modeling:

Created relationships between different tables for efficient data retrieval.

Used DAX measures to calculate key metrics such as Total Sales, Average Rating, Top-Selling Product Line, and Revenue per Customer Type.

# Visualizations:

Product Dashboard: Included bar charts, pie charts, and slicers for filtering product-wise sales.

Sales Dashboard: Implemented line graphs, KPI cards, and heatmaps to analyze daily and monthly trends.

Customer Dashboard: Added stacked column charts, donut charts, and scatter plots to study customer demographics and preferences.

# Interactivity & Filters:

Used slicers for dynamic filtering of sales by branch, city, and product line.

Drill-through functionality for in-depth analysis of key areas.

# Summary

By leveraging Power BI, we transformed raw sales data into meaningful insights that help businesses make data-driven decisions. The analysis covered product performance, sales trends, and customer behavior, enabling businesses to optimize their sales strategies and enhance profitability. With interactive dashboards, KPI indicators, and dynamic filters, Power BI has proven to be an essential tool in sales data analysis.
