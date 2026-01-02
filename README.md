📊 End-to-End Customer Purchase & Behaviour Analytics

Author: Aayush Kumbhar
Role: Data Analyst
Project Duration: 24 Dec 2025 – 31 Dec 2025

📌 Project Overview

This project demonstrates an end-to-end data analytics workflow that transforms raw customer shopping data into actionable business insights.

The analysis covers customer demographics, purchase behaviour, product performance, discounts, subscriptions, seasonality, and regional trends using Python, SQL, and Power BI.

The final output includes:

Cleaned and enriched data

SQL-based business analysis

Clearly defined KPIs

An interactive Power BI dashboard

Business-focused insights and recommendations

🎯 Business Problem

The business has access to customer shopping data, but the data is mostly raw and unstructured, making it difficult to:

Understand customer purchasing behaviour

Identify high-value customer segments

Track revenue drivers and performance trends

Support data-driven decision-making

As a result, valuable insights remain hidden within the data.

🎯 Objectives

The main objectives of this project were to:

Understand customer purchase behaviour and spending patterns

Identify key performance metrics related to revenue and retention

Segment customers based on behaviour and value

Analyse the impact of discounts, subscriptions, and seasons

Present insights through an interactive and easy-to-understand dashboard

🗂️ Dataset Overview

Source: Excel dataset

Size: ~3,900 rows × 19 columns (after preprocessing)

Data Includes:

Customer demographics

Order and purchase details

Subscription status

Discounts and shipping types

Payment methods

Product categories and ratings

Seasonal and regional information (USA)

🧹 Data Cleaning & Feature Engineering (Python – Pandas)

Key data preparation steps:

Handled 37 missing values in review_rating using category-wise median imputation

Created new features:

Age Group (Young Adult, Adult, Middle Age, Senior)

Purchase Frequency (Days) for numeric analysis

Removed redundant columns (promo_code_used) to reduce data duplication

After cleaning, the dataset was ready for SQL analysis and visualization.

🧮 SQL Analysis & Aggregations (MySQL)

SQL was used extensively for aggregation, segmentation, and comparative analysis, including:

Analysis Areas

Customer spending & revenue distribution

Subscription and retention behaviour

Discount effectiveness

Product performance and category analysis

Customer segmentation (New, Returning, Loyal)

Seasonal purchasing trends

Regional revenue performance

Payment method preference of high-value customers

Advanced SQL techniques used:

CTEs (Common Table Expressions)

Window functions (RANK, ROW_NUMBER)

Conditional aggregation

Customer-level revenue calculations

📈 KPIs Tracked

Key KPIs displayed in the dashboard:

Total Customers: 3,900

Total Revenue: $233K

Average Order Value (AOV): $59.76

Revenue per Customer: $59.8

Repeat Customer Rate: 97.87%

Average Review Rating: 3.75

Supporting KPIs include:

Revenue by gender and age group

Discount vs non-discount revenue

Category-wise purchases

Payment method usage

📊 Dashboard Overview (Power BI)

The Power BI dashboard provides an interactive view of:

Customer insights

Revenue distribution

Product and category performance

Seasonal and regional trends

Key Features

KPI cards for quick performance tracking

Filters for gender, age group, season, payment method, subscription status, and location

Regional sales map (USA)

Comparative visuals for discounts, subscriptions, and shipping types

The dashboard is designed for easy exploration and decision support.

🔍 Key Insights

Some of the major insights from the analysis include:

Male customers generate more than double the revenue compared to female customers

Subscription adoption is low (27%) and does not significantly increase spending

Discounts are effective for some products but ineffective for others

Customer retention is high (~86%), but 14% show long purchase gaps

Young customers contribute the highest revenue

Outerwear is a low-performing category

Fall is the strongest season; summer is the weakest

Certain US states generate lower revenue per customer

💡 Business Recommendations

Based on the insights:

Improve engagement and targeting for female customers

Redesign the subscription model to increase adoption and value

Optimize discount strategy by product type

Re-engage customers with long purchase gaps

Introduce bundle offers for adult and senior customers

Promote underperforming categories like outerwear

Run summer-focused campaigns to reduce seasonality impact

Use location-based promotions in low-performing regions

⚠️ Limitations

Analysis is based on historical data only

External factors such as marketing campaigns or economic conditions were not included

The project focuses on descriptive analysis; no predictive modeling was performed

Some assumptions during data cleaning may slightly affect results

🛠️ Tools & Technologies

Python (Pandas) – Data cleaning & feature engineering

MySQL Workbench – Data analysis & aggregation

Power BI – Dashboard & visualization

Excel – Raw data source

📌 Key Takeaway

This project demonstrates the ability to handle the complete analytics lifecycle — from raw data to business insights — using industry-standard tools and a business-focused mindset.
