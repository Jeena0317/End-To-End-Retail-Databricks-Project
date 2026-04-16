📊 Retail Data Pipeline (Databricks)
🚀 Overview

This project builds a data pipeline in Databricks using PySpark

It processes retail data from raw format to useful insights

🏗️ Flow
CSV File → Bronze → Silver → Gold
🛠️ Tools Used
Databricks
PySpark
Delta Lake
📥 Bronze Layer
Raw CSV data is loaded
Stored as a Delta table
No changes made
🔄 Silver Layer
Cleaned the data
Fixed null values
Converted date formats
Standardized text
Removed duplicates
Created total_amount
📊 Gold Layer
Aggregated data for analysis
Calculated total sales
Calculated total orders
Calculated average price
Created customer metrics
📈 KPI Table
Total revenue
Total customers
Average order value
📌 Output Tables
bronze_orders
silver_orders
gold_aggregates
gold_kpis_final
🎯 Conclusion

Built a simple end-to-end pipeline in Databricks

Converted raw data into clean and useful insights
