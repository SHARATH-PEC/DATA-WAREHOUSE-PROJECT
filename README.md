# 📊  Data Warehouse Project

## 📌 Project Overview

This project focuses on building a modern **Data Warehouse using Microsoft SQL Server** to consolidate, clean, transform, and organize CRM(Customer Relationship Management) data and ERP(Enterprise Resource Planning) data.

The primary objective is to transform raw data into structured, reliable, and analytics-ready information using the Medallion Architecture (Bronze, Silver, and Gold layers).

This project demonstrates practical Data Engineering concepts, including data ingestion, ETL processes, data transformation, data quality, and dimensional modeling.

## 🎯 Project Objectives

- Build a Data Warehouse from raw CRM and ERP datasets.
- Implement the Medallion Architecture.
- Load raw data into the Bronze layer.
- Clean and transform data in the Silver layer.
- Create business-ready datasets in the Gold layer.
- Apply SQL-based ETL processes.
- Develop a scalable and maintainable data pipeline.

## 🏗️ Data Warehouse Architecture

The project follows the Medallion Architecture.

```text
             SOURCE DATA
                  |
                  |
          CRM CSV DATASETS
                  |
                  v
          +---------------+
          | BRONZE LAYER  |
          | Raw Data      |
          +---------------+
                  |
                  v
          +---------------+
          | SILVER LAYER  |
          | Cleaned Data  |
          +---------------+
                  |
                  v
          +---------------+
          | GOLD LAYER    |
          | Business Data |
          +---------------+
                  |
                  v
          DATA ANALYTICS
          & REPORTING
```

### 🥉 Bronze Layer
- Stores raw data from source CSV files.
- Maintains the original data structure.
- Performs initial data ingestion.
- Minimizes transformations.

### 🥈 Silver Layer
- Cleans and standardizes data.
- Handles missing and duplicate records.
- Performs data validation.
- Integrates related datasets.

### 🥇 Gold Layer
- Creates business-ready datasets.
- Implements dimensional modeling.
- Organizes data for analytical queries.
- Supports reporting and decision-making.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft SQL Server | Data Warehouse Database |
| SQL / T-SQL | Data Processing and Transformation |
| SQL Server Management Studio (SSMS) | Database Management |
| CSV | Source Data Format |
| Git & GitHub | Version Control |

## 📂 Project Structure

```text
CRM-Data-Warehouse/
│
├── datasets/
│   └── CRM/
│       └── *.csv
│
├── projectcode/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── docs/
│
└── README.md
```

## ⚙️ Project Workflow

1. Collect CRM and ERP source datasets in CSV format.
2. Create the Data Warehouse database in SQL Server.
3. Create separate schemas for Bronze, Silver, and Gold.
4. Load raw CSV data into Bronze tables.
5. Clean and transform data in the Silver layer.
6. Create analytical models in the Gold layer.
7. Execute SQL queries for analysis and reporting.

## 📚 Key Data Engineering Concepts

This project helps demonstrate practical knowledge of:

- Data Warehouse Architecture
- ETL (Extract, Transform, Load)
- Medallion Architecture
- Data Ingestion
- Data Cleaning
- Data Transformation
- SQL Joins and Subqueries
- Window Functions
- Stored Procedures
- Views
- Data Modeling
- Fact and Dimension Tables

## 👨‍💻 Author

**S Sharath**

Engineering Student | Aspiring Data Engineer

Interests:
- Data Engineering
- SQL & Database Management
- Data Warehousing
- Artificial Intelligence

---

⭐ If you find this project interesting, consider giving the repository a star!
