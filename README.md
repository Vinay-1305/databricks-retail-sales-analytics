# Retail Sales Analytics Using Databricks

## Project Overview

This project demonstrates a Retail Sales Analytics solution built using Databricks. It focuses on analyzing sales data using SQL, exploring AI-assisted insights with Databricks Genie, and creating an interactive dashboard using Databricks AI/BI Dashboards.

## Objectives

* Organize sales data using Unity Catalog.
* Analyze overall sales performance using SQL.
* Identify the top-performing products and regions.
* Analyze monthly sales trends.
* Calculate product category revenue contributions.
* Explore business questions using Databricks Genie.
* Validate AI-generated insights against SQL results.
* Create an interactive sales analytics dashboard.

## Tools and Technologies

* Databricks
* Unity Catalog
* Databricks SQL
* Databricks Genie
* Databricks AI/BI Dashboards
* SQL

## Dataset Overview

The dataset contains 1,000 sales records and 100 distinct products.

The analysis uses fields including Product_ID, Sale_Date, Region, Sales_Amount, Quantity_Sold, and Product_Category.

## Unity Catalog Structure

```text
Innomatics
└── default
    └── sales_dataset
```

## Business Questions

1. What is the overall sales performance?
2. Which five products generated the highest total sales revenue?
3. Which region generated the highest sales revenue?
4. How does sales revenue change month by month?
5. Which product category contributes the most to total sales?

## Key Findings

| Metric                   |       Result |
| ------------------------ | -----------: |
| Total Sales Revenue      | 5,019,265.23 |
| Total Quantity Sold      |       25,355 |
| Total Sales Records      |        1,000 |
| Distinct Products        |          100 |
| Highest-Revenue Region   |        North |
| Highest-Revenue Category |     Clothing |
| Highest-Revenue Product  | Product 1099 |

## Genie Analysis

Databricks Genie was used to explore business questions in natural language. Its responses were compared with manually written SQL queries.

The initial top-five product results differed between Genie and SQL, demonstrating why AI-generated insights must be validated.

## Dashboard

The AI/BI Dashboard contains KPI cards for total revenue, quantity sold, sales records, and distinct products.

It also includes visualizations for sales by region, sales by category, monthly sales revenue, and the top 10 products, with interactive filters.

## Repository Contents

* SQL query files for the five business questions.
* Screenshots of the SQL results, Genie analysis, and dashboard.
* Project documentation and findings.

## Conclusion

This project provided practical experience in SQL-based sales analysis, data organization with Unity Catalog, AI-assisted exploration, validation of analytical results, and interactive dashboard development using Databricks.
