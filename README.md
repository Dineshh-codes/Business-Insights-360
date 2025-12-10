📊 Business Insights 360 – Power BI End-to-End Analytics Solution

This project represents a full Business Insight 360° analytics solution built for AtliQ Hardware, a global consumer electronics company operating through retail, distribution, and direct channels. After facing major losses in the Latin America market due to intuition-based decisions and Excel-driven reporting, the company began a BI transformation to bring transparency, accuracy, and data-driven decision-making across the organization.

This repository documents the end-to-end Power BI solution created as part of that initiative.
⚠️ Due to confidentiality, no datasets or PBIX reports are included.

🚀 Project Overview

The goal of this project was to provide leadership with a 360° view of business performance across Finance, Sales, Marketing, Supply Chain, and Executive functions. The analytics solution integrates multiple data sources, applies structured cleaning and transformation through Power Query and SQL, and uses a scalable star-schema model to support advanced DAX calculations.

The final solution delivers insights on:
• 📈 Revenue & margin trends
• 👥 Customer & product performance
• 🌍 Market-level analysis
• 🔄 Forecast accuracy & supply chain reliability
• 🏢 Executive summaries & company-wide KPIs

📊 Dashboard Views

Live Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMDIyMTBhYjktMzA1Ny00MjgwLWIwYzMtNjExMWQxNmZlNDg1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

1️⃣ Finance View – P&L & Profitability
Dynamic P&L reporting with drilldowns across customer, product, country, or any time period.

2️⃣ Sales View – Customer Insights
Customer performance benchmarking using Net Sales, Gross Margin %, Growth, and a Profitability/Growth matrix.

3️⃣ Marketing View – Product Insights
Performance comparison across products, categories, and segments using profitability and growth matrices.

4️⃣ Supply Chain View – Forecast Accuracy
KPIs including Forecast Accuracy, Net Error, and Risk Profiles across product categories and customer groups.

5️⃣ Executive View – Company Summary
High-level KPIs and insights consolidated for leadership decision-making.

🧱 Data Model (Star Schema)

📁 Dimension Tables
• dim_product
• dim_customer
• dim_market
• dim_date

📦 Fact Tables
• fact_sales_monthly
• fact_forecast_monthly
(merged into fact_actuals_estimate)

🔧 Supporting Fact Tables
• freight_cost
• manufacturing_cost
• pre_invoice_discount
• post_invoice_discount
• operational_costs
• gross_price
• targets

🛠 Tech Stack

• 🟡 Power BI – Dashboards, DAX, modeling
• 🔵 Power Query – ETL, data cleaning, transformation
• 🟣 SQL – Data extraction, joins, validation
• 🟢 Excel – Master & reference data
• ⚙️ DAX Studio – Performance tuning (storage ↓30%, speed ↑10%)

📈 Key Outcomes

• Enabled leadership to shift from Excel to BI-driven decision-making
• Improved transparency across financial, sales, and operational metrics
• Identified trends contributing to earlier regional losses
• Delivered interactive dashboards across 5 business functions
• Created a scalable analytics system supporting long-term reporting needs

📂 Repository Contents

• README.md – Project documentation
• Screenshots folder – Dashboard previews
⚠️ No data sources or PBIX files due to confidentiality

🎯 What This Project Demonstrates

• Strong Power BI & DAX development skills
• Multi-source ETL pipeline design (SQL + Power Query)
• Star schema modeling for analytics
• Cross-functional insights across Finance, Sales, Marketing & Supply Chain
• Ability to convert business needs into meaningful dashboards
• Clear storytelling through data

📄 License

This project is released under the MIT License.
(Datasets and PBIX files are not included.)
