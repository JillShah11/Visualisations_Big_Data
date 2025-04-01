# 📊 Databricks Data Visualizations – AdventureWorks Insights

## 🧾 Overview

This folder contains interactive data visualizations created in **Databricks** using **SQL queries and dashboards**. The visualizations are based on curated **Gold Layer** data from the AdventureWorks dataset, processed via the Medallion Architecture (Bronze → Silver → Gold).

The goal of these dashboards is to enable data-driven decision-making through clear, actionable insights.

---

## 📁 Visualization Categories

| Dashboard Name           | Description                                                      | Visual Types                       |
|--------------------------|------------------------------------------------------------------|------------------------------------|
| **Sales Overview**       | Tracks total sales, revenue, and YoY growth                     | Line charts, KPIs, bar charts      |
| **Returns Analysis**     | Analyzes return rates by product, category, and region           | Pie charts, heatmaps, stacked bars |
| **Product Performance**  | Identifies top-selling and underperforming products              | Column charts, bubble plots        |
| **Customer Insights**    | Segments customers by territory, purchase behavior, and loyalty  | Maps, bar charts, filters          |
| **Time Intelligence**    | Shows monthly and quarterly trends in sales and returns          | Time series, area charts           |

---

## 🔄 Data Source

All visualizations are based on Gold Layer data curated in **Azure Data Lake Storage** and loaded into **Databricks Delta tables**. These tables are the result of transformation pipelines from raw CSVs using PySpark.

| Table Name             | Description                                      |
|------------------------|--------------------------------------------------|
| `gold_sales`           | Aggregated sales by customer, date, product      |
| `gold_returns`         | Curated returns data                             |
| `dim_customers`        | Enriched customer profiles                       |
| `dim_products`         | Products with category and subcategory joins     |
| `dim_calendar`         | Full date dimension table                        |

---

## 📌 Features

✅ Interactive filters for year, region, and product category  
✅ Real-time querying of Delta tables  
✅ Easy export to PDF/CSV for reporting  
✅ KPI widgets for quick summary stats  
✅ Responsive layout for dashboards  

---

## 🛠️ Tools & Technologies

- 📈 **Databricks SQL Dashboards**  
- 📊 **Delta Lake** for performant querying  
- 💻 **PySpark** for data transformation  
- 🔗 **Azure Data Lake Storage (ADLS)**  
- 🔐 **Azure Key Vault** for secure access  

---

## 🖼️ Sample Screenshots

![image](https://github.com/user-attachments/assets/a422dfac-88e8-4ff3-916e-6b08c967aeab)

![image](https://github.com/user-attachments/assets/efa4bbfe-f9d7-45c9-99e0-ebe68f328384)

![image](https://github.com/user-attachments/assets/7d149222-be38-4264-ba8e-e0650cf348f0)


