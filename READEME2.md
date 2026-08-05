# Data Warehouse and Analytics project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 📖 Project Overview

This project involves:

1. **Data Architecture:** Designing a Modern Data Warehouse using the **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

---

## 🛠️ Important Links & Tools

Everything is **FREE!**

- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/sql/ssms/download-sql-server-management-studio-ssms):** GUI for managing and interacting with SQL Server databases.
- **[Draw.io](https://app.diagrams.net/):** Create architecture diagrams, ERDs, ETL flows, and process diagrams.
- **[Notion](https://www.notion.so/):** Organize project documentation, tasks, and notes.


---

## 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### 🎯 Objective

Develop a modern data warehouse using **SQL Server** to consolidate sales data, enabling analytical reporting and informed decision-making.

### 📋 Specifications

- **Data Sources:** Import data from two source systems (**ERP** and **CRM**) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues before analysis.
- **Integration:** Combine both source systems into a single, user-friendly analytical data model.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

## 🏗️ Project Architecture
 
The data architecture for this project follows **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers:
![Architecture](docs/data_architecture.png)

| Layer | Description |
|--------|-------------|
| 🥉 Bronze | Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.|
| 🥈 Silver |This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis. |
| 🥇 Gold | Houses business-ready data modeled into a star schema required for reporting and analytics. |

---

## 📁 Repository Structure

---


## 📊 Skills Demonstrated

- Data Warehousing
- ETL Development
- Data Modeling (Star Schema)
- SQL Development
- Data Cleaning & Transformation
- Analytical Reporting
- Database Design
- Documentation

---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.




