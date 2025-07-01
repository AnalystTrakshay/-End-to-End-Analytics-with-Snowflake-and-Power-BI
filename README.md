📊 End-to-End Analytics with Snowflake and Power BI
🔧 Project Summary
This project showcases a complete data analytics pipeline using Snowflake and Power BI, built around the Tasty Bytes sample dataset. It demonstrates how to transform raw data into a governed, real-time analytics model and visualize it using Power BI’s DirectQuery mode.

📁 Dataset: Tasty Bytes
The Tasty Bytes dataset simulates a global food truck business and includes:

Sales Transactions
Customer Profiles
Truck Locations
Menu Items
Weather Data
This dataset is structured in a star schema and is ideal for demonstrating real-time, multi-dimensional analytics.

🧰 Tools & Technologies
Snowflake: Cloud data platform for storage, transformation, and governance
Power BI: Business intelligence tool for visualization and reporting
Snowsight: Snowflake’s UI for data profiling and SQL development
Dynamic Tables: For building ELT pipelines declaratively
Snowflake Horizon: For data governance (masking, tagging, access control)
Power BI Template (.pbit): Pre-built semantic model for DirectQuery

🧠 Key Learnings
Profiling and transforming raw data using SQL in Snowsight
Enriching data with third-party datasets from the Snowflake Marketplace
Building a star schema optimized for analytics
Implementing row-level and column-level security
Connecting Power BI to Snowflake using DirectQuery for near real-time insights

📈 Insights & Visualizations
Sales Trends: Daily, weekly, and monthly performance
Top Menu Items: Revenue by item and category
Customer Behavior: Repeat purchases and loyalty
Weather Impact: Correlation between weather and sales
Geographic Analysis: Performance by truck and region

📌 Prerequisites
Completion of the [“Introduction to Tasty Bytes”](https://quickstarts.snowflake.com/) Quickstart ( This is link to get data into snowflake DB)
Snowflake account (free trial available)
Power BI Desktop
Access to Power BI Service (optional)


📂 What This Repo Includes
SQL scripts for data profiling and transformation
Power BI template file (.pbit)
DAX measures for trend analysis
Visual layout suggestions
Documentation for setup and usage
