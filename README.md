# Azure-Data-Engineering

https://colab.research.google.com/drive/1iy3FkueyUnh_Brq1hKVEKzpQ6uWjN8BL?usp=sharing

## Project Overview
This project demonstrates an end-to-end data engineering pipeline built on Microsoft Azure. It ingests raw CSV data, performs transformations using Databricks (Apache Spark), and stores the output in Parquet format for efficient querying and analytics.

## Tech Stack
- Microsoft Azure (Azure Data Lake Storage, Databricks)
- Apache Spark (PySpark)
- Parquet file format
- Python

## Pipeline Steps
1. **Data Ingestion:** Load raw CSV files from Azure Data Lake Storage.
2. **Data Transformation:** Clean and transform data using PySpark in Databricks notebooks.
3. **Data Storage:** Write the processed data back in Parquet format to Azure Data Lake for optimized access.
4. **Query & Analytics:** Enable downstream analytics workflows to run efficiently on Parquet files.
