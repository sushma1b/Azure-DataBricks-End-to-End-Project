# Azure Databricks End-to-End Data Engineering Project

**Overview:**  
Built an end-to-end data engineering pipeline on Azure Databricks using Lakehouse architecture principles.  
The project demonstrates how raw data is ingested, transformed, and optimized into analytics-ready datasets using PySpark, Spark SQL, and Delta Lake.  
This project mirrors real-world enterprise data platforms and aligns with Databricks Data Engineer Associate certification objectives.  

**Architecture:**
Medallion Architecture (Lakehouse):  
- Bronze - Raw data ingestion  
- Silver – Cleansed & standardized data  
- Gold – Aggregated, analytics-ready datasets  
- Storage and processing are handled using Delta Lake on Azure Data Lake via Databricks notebooks.  

**Tools & Technologies:**  
- Azure Databricks  
- Azure Data Lake Storage Gen2  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Parquet  

**Pipeline Highlights:**  
- Ingested raw data from Azure Data Lake into Delta tables  
- Applied data cleansing, transformations, and deduplication using PySpark  
- Built Gold-layer aggregations for analytical use cases  
- Queried curated datasets using Spark SQL  
- Designed reusable, modular Databricks notebooks  

**What I Learned:**  
- Building end-to-end ETL/ELT pipelines on Azure Databricks  
- Implementing Bronze–Silver–Gold data modeling  
- Using Delta Lake for ACID transactions and schema enforcement  
- Writing optimized PySpark transformations  
- Leveraging SQL on Lakehouse for analytics and reporting  
- Applying data engineering best practices in cloud environments  
