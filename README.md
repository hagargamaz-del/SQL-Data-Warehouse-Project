# 📊 SQL Data Warehouse Project

Building a modern data warehouse using **SQL Server**, including ETL processes, data modeling, and analytics.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** with three layers:

- **Bronze Layer**  
  Stores raw data as-is from source systems. Data is ingested from CSV files into SQL Server.

- **Silver Layer**  
  Performs data cleansing, standardization, and normalization to prepare data for analysis.

- **Gold Layer**  
  Contains business-ready data modeled using a **star schema** for reporting and analytics.

![Data Architecture](https://github.com/user-attachments/assets/c29f75f3-e52f-472b-b60b-fd209985f4a6)

---

## 📖 Project Overview

This project includes:

- **Data Architecture**  
  Designing a modern data warehouse using the Medallion Architecture.

- **ETL Pipelines**  
  Extracting, transforming, and loading data from source systems into the warehouse.

- **Data Modeling**  
  Creating fact and dimension tables optimized for analytical workloads.

- **Analytics & Reporting**  
  Building SQL-based reports and dashboards to generate actionable insights.

---


## 🛠️ Tools & Resources

All tools used in this project are free:

- **Datasets**  
  CSV files used as source data.

- **SQL Server Express**  
  Lightweight database server for hosting the warehouse.

- **SQL Server Management Studio (SSMS)**  
  GUI for database management and querying.

- **GitHub**  
  Version control and collaboration platform.

- **Draw.io**  
  For designing architecture diagrams and data models.

- **Notion**  
  Project planning and documentation:
  - Project Template  
  - Project Steps (phases and tasks)

---

## 🚀 Project Requirements

### 🏗️ Data Engineering — Building the Data Warehouse

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data for analytical reporting and decision-making.

#### Specifications

- **Data Sources**  
  Import data from two systems:
  - ERP  
  - CRM  
  (provided as CSV files)

- **Data Quality**  
  Clean and resolve inconsistencies before analysis.

- **Integration**  
  Merge both sources into a unified, analytics-friendly data model.

- **Scope**  
  Focus on the latest dataset only (no historization required).

- **Documentation**  
  Provide clear data model documentation for:
  - Business stakeholders  
  - Analytics teams  

---

### 📊 Data Analysis — BI, Analytics & Reporting

#### Objective
Develop SQL-based analytics to generate insights on:

- Customer Behavior  
- Product Performance  
- Sales Trends  

#### Outcome
Deliver key business metrics that support **data-driven decision-making**.

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.
