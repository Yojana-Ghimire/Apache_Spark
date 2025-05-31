# Databricks PySpark ETL Pipelines

## Project Overview

This project demonstrates the development of multiple scalable ETL pipelines built on **Databricks** using **PySpark**, the Python API for Apache Spark.

The pipelines ingest data from various sources such as **CSV**, **Parquet**, and **Delta Tables**, applying a robust design to handle multiple data formats and processing needs.

---

## Key Features

- **Multiple Data Sources:** Supports CSV, Parquet, and Delta Table formats.
- **Factory Design Pattern:**  
  Implemented a Factory Pattern to create reader classes dynamically based on the data source type. This design pattern enhances modularity and flexibility, which is essential in complex data engineering pipelines.
- **Transformation Logic:**  
  Business logic is applied using PySpark DataFrame API and Spark SQL for efficient and scalable data processing.
- **Flexible Data Loading:**  
  Data is loaded into two types of storage:
  - **Data Lake:** For raw and curated data storage.
  - **Data Lakehouse:** Supports hybrid batch and interactive analytics with Delta Lake optimizations.

---

## Technologies Used

- Apache Spark (PySpark)  
- Databricks  
- Delta Lake  
- Python  
- Git & GitHub  

---

## Project Structure
# Reader classes following Factory Pattern
├── transformations/ # Business logic and Spark SQL scripts
├── loaders/ # Data loading modules (Data Lake & Lakehouse)
├── notebooks/ # Databricks notebooks exported (.ipynb)
├── requirements.txt # Python dependencies
└── README.md # This documentation
