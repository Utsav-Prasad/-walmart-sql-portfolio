<h2>Walmart Retail Insight Optimization</h2>

A professional SQL portfolio project focused on analyzing large-scale Walmart retail data using advanced MySQL techniques. This project demonstrates business intelligence, customer analytics, inventory optimization, and KPI reporting through real-world SQL use cases.

Based on a simulated retail environment containing 500K+ transactions, the project applies analytical SQL concepts such as:

Window Functions
Common Table Expressions (CTEs)
RFM Customer Segmentation
Stored Procedures
Query Optimization
Trend Analysis
Inventory Analytics
Project Overview

This project analyzes retail sales across:

500K+ transactions
45 store locations
5 dimensional tables
12 analytical SQL queries
18 business KPIs
6 months of retail data

The portfolio is designed to showcase practical SQL skills used in modern data analytics and business intelligence roles.

Key Features
Advanced SQL Techniques
CTEs
Window Functions (RANK, LAG, ROW_NUMBER, NTILE)
Aggregate Functions
Stored Procedures
Conditional Aggregation
Self Joins
Ranking & Partitioning
Business Analytics
Revenue analysis
Customer segmentation
Inventory optimization
Cohort retention analysis
Market basket analysis
Payment trend analysis
KPI automation
Interactive HTML Portfolio

The project is presented through a professionally designed HTML dashboard containing:

Database schema
SQL query showcase
Business insights
KPI cards
Styled SQL blocks
Analytical findings
Database Schema

The project uses a star schema architecture.

Fact Table
fact_sales
Dimension Tables
dim_stores
dim_products
dim_customers
dim_date
SQL Queries Included
Query File	Objective	Technique
01_store_revenue_ranking.sql	Store revenue ranking	CTE + RANK()
02_rfm_segmentation.sql	Customer segmentation	NTILE()
03_mom_growth.sql	Monthly growth analysis	LAG()
04_slow_inventory.sql	Inventory optimization	HAVING + CASE
05_category_contribution.sql	Revenue contribution	ROLLUP
06_holiday_vs_normal.sql	Holiday sales analysis	Conditional Aggregation
07_payment_method_trend.sql	Payment trends	CASE Pivoting
08_cohort_retention.sql	Customer retention	Self Join
09_top_products_store.sql	Top products per store	ROW_NUMBER()
10_supplier_performance.sql	Supplier analysis	Multi-table JOIN
11_basket_analysis.sql	Market basket analysis	Self Join
12_store_proc_daily_kpi.sql	Automated KPI report	Stored Procedure
Business Insights Generated

Some major findings from the analysis include:

Southwest region generated the highest revenue
Members spend significantly more than non-members
Champion customers contribute a large share of total revenue
At-risk customers were identified for re-engagement campaigns
Slow-moving inventory products were detected
Weekend and holiday sales showed strong transaction spikes
Technologies Used
MySQL 8.0
HTML5
CSS3
Advanced SQL
Data Analytics Concepts
