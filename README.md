# 🏗️ Data Warehouse & Analytics Project

*A hands-on project inspired by Baraa’s YouTube tutorial: [Build a Data Warehouse & Analytics Solution](https://youtu.be/9GVqKuTVANE?si=s2PsroVhGY3EvNSS)*

---

## 🎯 Project Goal

To build a **modern data warehousing and analytics solution** from the ground up—starting with raw datasets, designing the architecture, building ETL pipelines, modeling data for analysis, and ultimately generating actionable insights. This project is structured following **industry best practices** in **data engineering** and **analytics**.

---

## 🏛️ Data Architecture

The architecture is based on the **Medallion Architecture**, a layered approach to organizing data for scalability, quality, and analytics readiness:

### ➤ Bronze Layer
- Raw ingestion layer  
- Stores untransformed, historical data from source systems

### ➤ Silver Layer
- Cleansed and joined data  
- Conforms raw data to business logic

### ➤ Gold Layer
- Final analytical layer  
- Optimized for reporting, dashboards, and business intelligence

---

## 📌 Project Overview

This project includes the following key phases:

1. **Data Architecture**
    - Design and implement a Medallion-based data architecture
    - Create appropriate schemas for each layer (Bronze, Silver, Gold)
2. **ETL Pipelines**
    - Extract, Transform, and Load data from source CSV files
    - Implement **Truncate & Insert** logic in the Bronze Layer
3. **Data Modeling**
    - Build dimension and fact tables in the Silver/Gold layers
    - Optimize for query performance and analytics use cases

---

## 📄 Project Report

View the full project documentation and progress on Notion:  
🔗 [Notion Report – Data Warehouse Project](https://www.notion.so/Report-Data-Warehouse-Project-1f71a18bc9a380419e15c96dff45facb?source=copy_link)

---

## 🧰 Tools & Technologies

| Tool | Description |
|------|-------------|
| [**Datasets (CSV)**](https://github.com/DataWithBaraa/sql-data-warehouse-project/blob/main/datasets) | Sample datasets used in the project |
| [**SQL Server Express**](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) | Lightweight SQL database server |
| [**SSMS**](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16) | SQL Server Management Studio – for DB development & querying |
| **GitHub** | Version control and code hosting |
| **Canvas / Diagrams** | Architecture and ETL flow design visuals |
