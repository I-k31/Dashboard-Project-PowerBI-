Department Store Revenue Analysis (2017–2022)
Overview:
This project analyzes 6 years of revenue data from a department store dataset sourced from Kaggle. Using T-SQL to query and aggregate the data, and Power BI to visualize it, the goal was to identify revenue trends across departments over time.
Dataset: Department Store Sales Dataset: https://www.kaggle.com/datasets/raphaelpuziol/department-store-sales-dataset/data — Kaggle
Tools

SQL Server Management Studio (SSMS) — data querying and aggregation
T-SQL — conditional aggregation to pivot revenue by year
Power BI — dashboard creation and visualization

Methodology:

Loaded the dataset into SQL Server Management Studio
Wrote a T-SQL query using conditional aggregation (SUM(CASE WHEN ... END)) to calculate total revenue per department for each year from 2017 to 2022
Grouped results by department to produce a year-over-year revenue comparison table
Imported the query output into Power BI to build an interactive dashboard

Key Findings:

Total revenue more than doubled from 28.22M in 2017 to a peak of 57.72M in 2018
Revenue declined every year from 2018 onward, falling to 11.61M by 2022
Eletrônicos (Electronics) was the highest-revenue department consistently across all years
Papelaria (Stationery) and Acessórios (Accessories) were the lowest-revenue departments throughout the period

Dashboard
The Power BI dashboard includes:

A line chart comparing revenue across all 7 departments by year
KPI cards displaying total revenue for each year (2017–2022)
