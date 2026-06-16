# 📊 AtliQ Hardware Sales & Finance Analytics Report

## Overview

This project focuses on analyzing the sales and financial performance of AtliQ Hardware using Microsoft Excel. The analysis was conducted using Power Query, Power Pivot, Data Modeling, DAX, and Pivot Tables to generate business reports and derive actionable insights.

AtliQ Hardware is a manufacturer and distributor of hardware products such as PCs, printers, keyboards, and accessories, serving customers through retailers, distributors, and e-commerce channels across multiple countries.

---

## Project Objectives

* Analyze customer and market sales performance.
* Compare actual sales against business targets.
* Identify top and bottom-performing products.
* Evaluate financial performance using key metrics.
* Generate business reports to support decision-making.

---

## Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot
* DAX (Data Analysis Expressions)
* Data Modeling (Star Schema)
* Pivot Tables
* ETL Process

---

## Dataset

The analysis was performed using the following tables:

* dim_customer
* dim_product
* dim_market
* dim_date
* fact_sales_monthly_with_cost
* ns_targets_2021

---

## ETL Process

1. Extracted raw CSV files.
2. Loaded data into Power Query.
3. Performed data cleaning and transformation.
4. Created relationships between tables.
5. Built a Star Schema data model.
6. Created DAX measures for analysis.
7. Generated analytical reports using Pivot Tables and Power Pivot.

---

## Data Modeling

A Star Schema was implemented with:

### Fact Table

* fact_sales_monthly_with_cost

### Dimension Tables

* dim_customer
* dim_product
* dim_market
* dim_date

This model enables efficient reporting and analysis.

---

## DAX Measures Created

* Net Sales
* Gross Margin
* Gross Margin %
* Sales 2019
* Sales 2020
* Sales 2021
* Target Sales 2021
* 2021 vs 2020 Comparison
* Target Achievement %

---

## Sales Analytics Reports

### Customer Net Sales Performance

* Customer-wise sales analysis from 2019–2021.
* Year-over-year sales growth comparison.
* Market and region-level filtering.

### Market Performance vs Target

* Analysis of actual sales against 2021 targets.
* Identification of countries with the largest sales gaps.

### Top 10 Products Analysis

* Comparison of top-performing products in 2021 versus 2020.
* Growth trend analysis.

### Division-Level Report

* Performance comparison across N&S, P&A, and PC divisions.

### Top & Bottom Selling Products

* Product ranking based on quantity sold.

### New Products Introduced in 2021

* Identification of products launched during FY 2021.

---

## Finance Analytics Reports

### P&L by Fiscal Year

Analysis of:

* Net Sales
* Cost of Goods Sold (COGS)
* Gross Margin
* Gross Margin %

### P&L by Quarter

Quarter-wise comparison of:

* Revenue
* COGS
* Gross Margin

### Gross Margin Analysis

Comparison of Gross Margin % across different regions and fiscal years.

---

## Key Insights

### Sales Insights

* Net Sales increased from $87.5M in 2019 to $598.9M in 2021.
* Significant growth observed across all business divisions.
* India and the USA emerged as major revenue contributors.

### Financial Insights

* Gross Margin increased substantially alongside revenue growth.
* Gross Margin % showed a slight decline despite higher sales.
* Regional profitability varied significantly across markets.

---

## Key Learnings

* ETL Process in Excel
* Power Query Transformations
* Data Modeling
* DAX Calculations
* Sales Analytics
* Finance Analytics
* Business Reporting
* KPI Analysis

---

## Project Outcome

This project demonstrates how Excel can be used as a powerful Business Intelligence tool to transform raw business data into meaningful reports and actionable insights for decision-making.

---

## Author

**Gagandeep Kaur**

Aspiring Data Analyst | Excel | SQL | Power BI | Data Analytics

LinkedIn: www.linkedin.com/in/gagandeepkaurbhatti
