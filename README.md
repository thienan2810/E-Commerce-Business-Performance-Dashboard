# E-Commerce-Business-Performance-Dashboard

## Project Overview
This project focuses on building an interactive Business Performance Dashboard using **Power BI** to analyze and monitor key operational metrics for an e-commerce business. The dashboard transforms raw transactional data into actionable insights, helping stakeholders track sales trends, customer growth, and shipping efficiency.

<img width="1149" height="646" alt="image" src="https://github.com/user-attachments/assets/ea4778b7-e6b3-4028-8cbb-ce9ba1fa119a" />

## Key Metrics & Features
* **Total Orders:** 9,999 successful orders tracked.
* **Total Customers:** 6,128 unique customers.
* **Total Revenue:** 24.78M dynamic revenue calculation.
* **Completion Rate:** 67.05% order fulfillment breakdown.
* **Monthly & Daily Performance:** Time-series analysis showcasing order volume and revenue fluctuations from late 2023 through 2024.
* **Fulfillment Analysis:** Visual representation of order status (Completed vs. Cancelled) and shipping methods (Express, Overnight, Standard).

## Data Pipeline & Technical Implementation

### 1. Data ETL (Extract, Transform, Load)
* Imported raw transactional data into **Power BI Desktop**.
* Utilized **Power Query** to clean data, handle missing values, format data types (dates, currency), and prepare tables for modeling.

### 2. Data Modeling & DAX
* Established relationship connections between tables to form a clean, functional data schema.
* Wrote baseline **DAX (Data Analysis Expressions)** formulas to calculate key performance indicators (KPIs) including Total Orders, Unique Customers, and Order Completion Percentages.

### 3. Data Visualization & Dashboard Design
* Implemented a user-friendly layout with a clear hierarchy: high-level KPI cards at the top, followed by structural breakdowns (Donut & Bar charts), and granular data grids (Matrix table) for deep-dives.
* Applied consistent color coding to distinguish between different order statuses and shipping types.

## Tools Used
* **Power BI Desktop** (Power Query, DAX, Data Visualization)
* **Microsoft Excel** (Data preparation)
