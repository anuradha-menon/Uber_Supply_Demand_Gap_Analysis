Uber Supply-Demand Gap Analysis

Welcome to the Uber Supply-Demand Gap Analysis project! This repository contains all the code, data, and documentation for analyzing Uber ride request data to uncover patterns and gaps between customer demand 
and driver supply.

Project Overview:

This project investigates Uber’s operational data to identify when and where there is a mismatch between ride demand and available supply. The analysis leverages data cleaning, SQL aggregation, Excel dashboards, 
and Python visualizations to provide actionable business insights.

Dataset:

Source: Uber ride request data (CSV format)
Fields: Request ID, Pickup Point, Driver ID, Status, Request Timestamp, Drop Timestamp, Hour, Day of Week, etc.
Status Values: Trip Completed, Cancelled, No Cars Available

Setup & Requirements:

Prerequisites:

Python pandas, numpy, seaborn, matplotlib (for Python analysis)
Excel 2016+ (for dashboard)
Any SQL database (MySQL, SQLite, etc.)

How to Use:

1. Data Preparation
Clean raw data in Excel (remove blanks, standardize dates).
Save as uber_requests.csv in the data/ folder.

2. SQL Analysis
Import the CSV into your SQL database.
Run queries from sql/queries.sql to generate summary tables and metrics.

3. Excel Dashboard
Open excel/Uber_Dashboard.xlsx.
Refresh PivotTables and charts to visualize supply-demand gaps, trends, and KPIs.

4. Python Visualization
Open python/analysis_notebook.ipynb.
Run the notebook for advanced charts (e.g., violin plots, time series).

Key Analyses:

Demand vs. Supply Summary: Total requests, completed trips, unmet demand, gap percentage.

Status Distribution: Share of each status (completed, cancelled, no cars).

Hourly & Daily Trends: When gaps are most severe.

Pickup Point Analysis: City vs. Airport demand patterns.

Driver-Level Analysis: Top drivers, cancellations, fulfillment rates.

Excel Dashboard Guide:

PivotTables: Analyze by status, hour, day, pickup point, and driver.
Charts: Stacked columns, line charts, heatmaps, KPI cards.
Slicers: Filter dashboard by time, location, or status for interactive exploration.

SQL Queries:

Find all SQL queries in sql/queries.sql, including:
Total and unmet demand calculation
Status breakdowns
Hourly and daily aggregation
Driver-level summaries

Python Scripts:

The Jupyter notebook python/analysis_notebook.ipynb contains:
Data cleaning and preprocessing
Calculation of supply-demand gap metrics
Violin plot and other advanced visualizations

Results & Insights:

Peak Gaps: Early morning and late evening hours, especially at the airport.

Root Causes: Driver shortages, demand surges, and cancellations.

Recommendations: Targeted driver incentives, dynamic pricing, operational improvements.


Happy analyzing! 
Empower Uber operations with data-driven insights.
