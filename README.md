# 📊 Data Warehouse and Analytics Project

This repository contains my end-to-end Data Warehouse and Analytics project built using SQL Server and Medallion Architecture (Bronze, Silver, Gold). The project demonstrates how raw operational data can be transformed into business-ready analytical models that support data-driven decision-making.

---

## 🏗️ Architecture Overview

The warehouse follows the Medallion Architecture pattern:

| Layer | Purpose |
|-------|----------|
| Bronze | Raw ingestion from ERP & CRM CSV files into SQL Server |
| Silver | Data cleaning, standardization, and validation |
| Gold | Business-ready star schema for analytics and reporting |

This layered design improves data quality, traceability, and performance.

---

## 📖 Project Objectives

### Data Engineering
- Ingest data from ERP and CRM source systems (CSV files)
- Clean and standardize inconsistent and missing data
- Integrate multiple sources into a unified warehouse
- Model analytical tables using a star schema
- Document datasets and transformations

### Analytics & Reporting
Deliver SQL-based insights into:
- Customer behavior
- Product performance
- Sales trends

---

## 🛠️ Technology Stack

- Database: SQL Server Express  
- ETL: SQL (T-SQL)  
- Modeling: Star schema  
- Documentation: Markdown, Draw.io  
- Version Control: Git, GitHub  


## 📜 License

This project is released under the MIT License.




