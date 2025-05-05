# SQL-Data-Warehouse-Project

Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

---

## Data Warehouse and Analytics Project

This project demonstrates a comprehensive data warehousing and analytics solution — from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## Data Architecture

The data architecture for this project follows the **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers:

![Data Architecture](docs/Data%20Architecture.png)

- **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server database.
- **Silver Layer**: Includes data cleansing, standardization, and normalization processes to prepare data for analysis.
- **Gold Layer**: Houses business-ready data modeled into a star schema, optimized for reporting and analytics.

---

## 📖 Project Overview

This project involves:

- **Data Architecture**: Designing a modern data warehouse using Medallion Architecture.
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## 🧰 Tools & Technologies

- **Datasets**: CSV files as data sources.
- **SQL Server Express**: Lightweight server for hosting the SQL database.
- **SQL Server Management Studio (SSMS)**: GUI for managing and querying databases.
- **Git**: Version control and collaboration via GitHub.
- **Draw.io**: For designing data architectures and diagrams.

---

## ⚙️ Specifications

- **Data Sources**: ERP and CRM data imported via CSV files.
- **Data Quality**: Cleansing and resolving issues prior to analysis.
- **Integration**: Combining both sources into a single, user-friendly data model.
- **Scope**: Focused on the latest dataset (no historization).
- **Documentation**: Clear documentation of the data model for business and analytics teams.
- **BI Output**: SQL-based analytics and visualizations.

---

## 🎯 Objective

Deliver SQL-based insights into:

- Customer Behavior
- Product Performance
- Sales Trends

These insights empower stakeholders with actionable metrics for strategic decision-making.

---

## 📂 Additional Resources

For more details, refer to the [docs](./docs).

---

## 🌟 About Me

Hi there! I'm **Declan Rhys Dkhar Phanbuh**, an IT professional on a mission to expand my knowledge and make working with data enjoyable and engaging!

