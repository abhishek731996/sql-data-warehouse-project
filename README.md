📊 Data Warehouse & Analytics Project
Welcome to the Data Warehouse & Analytics Project repository! 🚀
This project showcases an end-to-end implementation of a modern data warehousing and analytics pipeline — from raw data ingestion to delivering meaningful business insights. Built as a portfolio project, it reflects industry-standard practices in data engineering, data modeling, and analytics.

🏗️ Data Architecture Overview
This project is structured using the Medallion Architecture, following a layered approach to data processing and refinement:

🟫 Bronze Layer – Raw Data Ingestion
Raw, unprocessed data is ingested directly from CSV files.

The data is stored in a SQL Server database exactly as received from the source systems.

Purpose: Ensures traceability, auditing, and debugging capability.

🟪 Silver Layer – Data Transformation
Cleansed and standardized data is stored here.

Includes data cleaning, type casting, deduplication, and normalization.

Prepares data for reliable analysis and modeling.

🟨 Gold Layer – Business-Ready Data
Transformed into a Star Schema suitable for reporting.

Serves as the foundation for dashboards, KPIs, and business intelligence use cases.
