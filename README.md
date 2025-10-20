# Earthquake Lakehouse on Azure & Databricks

## Problem Statement

This project aims to continuously track global earthquake activity by ingesting real-time data from the USGS Earthquake API. The objective is to build a modern data engineering pipeline that processes, optimizes, and delivers this seismic data efficiently for analytics and consumption by final users.

## Project Description

This repository implements an end-to-end Medallion Lakehouse architecture on **Azure** and **Databricks**, following the **Bronze → Silver → Gold** layered approach:

* **Bronze**: Raw ingestion from the USGS Earthquake API
* **Silver**: Data cleaning, normalization, and schema enforcement
* **Gold**: Aggregated, analytics-ready data for reporting or downstream applications

![pipeline graph.png](https://github.com/EnriqManComp/earthquake-lakehouse-azure-databricks/blob/master/pipeline%20graph.png)

Data is stored in an optimized **Delta Lake / Parquet format**, enabling ACID transactions, time travel, and efficient querying.

## Technologies Used

* **Azure Databricks**
* **Azure Data Lake Storage (ADLS Gen2)**
* **Databricks Delta Lake**
* **Python / PySpark**
* **USGS Earthquake API**

More sections coming soon: architecture diagram, notebook breakdown, and deployment instructions.

