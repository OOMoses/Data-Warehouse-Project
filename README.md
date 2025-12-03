# Data Warehouse Project

This project demonstrates a comprehensive data warehousing solution. It is designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture follows the **Medallion Architecture** consisting of Bronze, Silver, and Gold layers:

![Data Architecture](docs/data_architecture_image.png)

### **1. Bronze Layer**
- Stores **raw data as-is** from source systems.  
- Data is ingested from **CSV files** into a **SQL Server database**.

### **2. Silver Layer**
- Performs **data cleansing**, **standardization**, and **normalization**.
- Prepares data for downstream analytical processes.

### **3. Gold Layer**
- Contains **business-ready data**, modeled into a **Star Schema**.
- Optimized for analytics and reporting.

---

## 📌 Project Overview

This project includes:

1. **Data Architecture** – Designing a modern data warehouse using the Medallion Architecture (Bronze → Silver → Gold).
2. **ETL Pipelines** – Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modelling** – Creating fact and dimension tables optimized for analytical queries.

### Skills Demonstrated
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modelling  

---

## 📂 Project Requirements

### **Building the Data Warehouse (Data Engineering)**

#### **Objective**
Develop a modern data warehouse using **SQL Server** to consolidate sales data, enabling analytical reporting and informed decision-making.

#### **Specifications**
- **Data Sources:** Import data from two source systems (**ERP** and **CRM**) provided as CSV files.  
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.  
- **Integration:** Combine both sources into a single, user-friendly **analytical data model**.  
- **Scope:** Focus on the **latest dataset only**; historization is *not* required.  
- **Documentation:** Provide clear documentation of the data model for both business stakeholders and analytics teams.  

---
