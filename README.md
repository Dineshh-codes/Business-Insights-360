⭐ Business Insights 360 – Power BI End-to-End Analytics Solution

This project represents a full Business Insight 360° analytics solution built for AtliQ Hardware, a global consumer electronics company expanding across multiple channels. After facing major losses in Latin America due to intuition-based decisions and Excel-driven reporting, the company initiated a BI transformation to bring transparency, accuracy, and data-driven decision-making into its operations.

This repository documents the end-to-end Power BI solution created as part of that initiative.
(Note: Due to confidentiality, no datasets or PBIX reports are included.)

🚀 Project Overview

The goal of this project was to give leadership a 360° view of business performance across Finance, Sales, Marketing, Supply Chain, and Executive functions.
The analytics solution integrates multiple data sources, applies structured cleaning and transformation through Power Query and SQL, and implements a scalable star schema model to support advanced DAX analysis.

The final solution delivers insights on:

Revenue and margin trends

Customer and product performance

Market-level growth

Supply chain forecast accuracy

Executive-level KPIs and summaries

This simulates how modern enterprises evolve from Excel-based workflows to a BI-driven analytics ecosystem.

📊 Dashboard Views (Business-Focused Summary)
1️⃣ Finance View – P&L & Profitability

A dynamic P&L report enabling profitability analysis at any level—market, customer, product, or a combination.

2️⃣ Sales View – Customer Insights

Customer performance benchmarking using Net Sales, Gross Margin %, Growth, and a Profitability/Growth matrix.

3️⃣ Marketing View – Product Insights

Product-level profitability and growth matrices to highlight top and underperforming SKUs and categories.

4️⃣ Supply Chain View – Forecast Accuracy

KPIs for Reliability, Forecast Accuracy, Net Error, and Risk Profiles across product categories and segments.

5️⃣ Executive View – Cross-Functional Summary

A consolidated, leadership-ready view highlighting the most critical metrics across all business functions.

🧱 Data Model (High-Level)

A structured analytics model using the following tables:

Dimension Tables

dim_product

dim_customer

dim_market

dim_date

Fact Tables

fact_sales_monthly

fact_forecast_monthly
(combined into fact_actuals_estimate)

Supporting Fact Tables

freight_cost

manufacturing_cost

pre_invoice_discount

post_invoice_discount

operational_costs

gross_price

targets

This enables a clean star schema optimized for clarity, performance, and scalability.

🛠 Tech Stack
Tool	Purpose
Power BI	Modeling, DAX, interactive dashboards
Power Query	ETL, data cleaning & transformation
SQL	Source extraction, joins, validations
Excel	Master/reference datasets
DAX Studio	Performance tuning and optimization
📈 Key Outcomes

Transitioned leadership from Excel-driven insights to a modern BI framework

Improved visibility across financial, operational, and commercial metrics

Provided actionable insights on customer, product, and market performance

Identified patterns contributing to past regional losses (e.g., Latin America)

Created a scalable analytics layer that supports strategic decisions

📂 Repository Contents

README.md – Full project documentation

Screenshots Folder (if available) – High-level previews

Model & Workflow Notes – Descriptions of transformations and logic

No datasets or PBIX files (restricted due to confidentiality)

🎯 What This Project Demonstrates

Real-world BI problem solving

Ability to convert business problems into data models and dashboards

Strong Power BI, DAX, and data modeling expertise

Multi-source ETL pipeline experience

Cross-functional analytics across Finance, Sales, Marketing, and Supply Chain

Executive-level storytelling and KPI design

📄 License

This project is licensed under the MIT License.
(All analysis logic is shared; datasets and PBIX files are not included.)
