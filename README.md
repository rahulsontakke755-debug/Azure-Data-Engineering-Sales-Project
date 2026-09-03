# Azure Data Engineering Sales Project

## 📌 Project Overview

This is an end-to-end Data Engineering project built using Microsoft Azure services. The project demonstrates how sales data can be ingested, processed, transformed, and stored using a modern Data Lakehouse architecture.

## 🏗️ Architecture

The project follows the **Medallion Architecture**:

* 🥉 **Bronze Layer** – Raw data ingestion
* 🥈 **Silver Layer** – Data cleaning and transformation
* 🥇 **Gold Layer** – Business-ready fact and dimension tables

## 🛠️ Technologies Used

* Azure Data Factory
* Azure Data Lake Storage Gen2
* Azure Databricks
* PySpark
* Delta Lake
* Event Hubs
* Auto Loader
* Change Data Feed (CDF)
* Liquid Clustering
* File Compaction
* Z-Ordering

## 🔄 Data Engineering Pipeline

1. Data is ingested using **Azure Data Factory** and streaming components.
2. Raw data is stored in the **Bronze Layer**.
3. **Auto Loader** is used for incremental file ingestion.
4. Data is cleaned and transformed using **PySpark** in Azure Databricks.
5. Processed data is stored in the **Silver Layer**.
6. Business-ready **fact and dimension tables** are created in the Gold Layer.
7. **Delta Lake** features are used for reliable data management and incremental processing.
8. **CDF, Liquid Clustering, File Compaction and Z-Ordering** are implemented for data tracking and performance optimization.

## 📊 Data Model

The Gold Layer contains:

* `fact_sales`
* `dim_customer`
* `dim_product`
* `dim_date`

## 🎯 Key Features

* End-to-end Azure Data Engineering pipeline
* Lakehouse architecture
* Medallion Architecture
* Incremental data ingestion
* Streaming data processing
* Delta Lake implementation
* Change Data Feed (CDF)
* Data optimization using Liquid Clustering and Z-Ordering
* Fact and Dimension data modeling

## 👨‍💻 Project Objective

The objective of this project is to build a scalable and reliable data pipeline that can process sales data efficiently and prepare it for analytical use cases.

## 🚀 Skills Demonstrated

**Azure | PySpark | Databricks | SQL | Data Lakehouse | ETL/ELT | Delta Lake | Data Engineering**

