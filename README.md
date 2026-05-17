# SQL Data Warehouse Project using Medallion Architecture

## Overview
This project demonstrates the implementation of a modern SQL Server Data Warehouse using the Medallion Architecture approach. The solution processes CRM and sales datasets through Bronze, Silver, and Gold layers to transform raw data into analytics-ready business models.

The project focuses on:
- ETL pipeline development
- Data transformation and cleansing
- Dimensional modeling
- Analytical reporting structures
- SQL Server stored procedures and automation

---

# Architecture

## Medallion Architecture

### Bronze Layer
Stores raw source data exactly as received from CSV files.

### Silver Layer
Performs data cleaning, transformation, standardization, and enrichment.

### Gold Layer
Provides business-ready dimensional models and analytical views for reporting and analytics.

---

# Technologies Used

- Microsoft SQL Server
- Stored Procedure
- Data Warehousing
- ETL Pipelines
- Star Schema Concepts

---

# Project Structure

```text
sql-data-warehouse-project/
│
├── datasets/
│   ├── cust_info.csv
│   ├── prd_info.csv
│   ├── sales_details.csv
│   ├── CUST_AZ12.csv
│   ├── LOC_A101.csv
│   └── PX_CAT_G1V2.csv
│
├── CodeFiles/
│   ├── init_database.sql
│   ├── ddl_bronze.sql
│   ├── proc_load_bronze.sql
│   ├── ddl_silver.sql
│   ├── proc_load_silver.sql
│   └── ddl_gold.sql
│
└── README.md
