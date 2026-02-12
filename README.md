# 📊 SQL Data Warehouse Project  

**End-to-End Modern Data Warehouse Implementation using SQL Server (ETL, Medallion Architecture & Analytics)**

---

## 🔍 Project Overview

This project demonstrates the end-to-end design and implementation of a modern **Data Warehouse** using **SQL Server** and industry-standard data engineering principles.

The solution transforms raw retail transaction data into an analytics-ready repository optimized for reporting and business intelligence. It simulates a real-world BI environment where operational data must be structured for scalable analytical querying.

📌 Key focus areas:
- Designing a scalable data warehouse architecture
- Implementing ETL (Extract → Transform → Load) workflows
- Applying Medallion Architecture (Bronze → Silver → Gold)
- Building a Star Schema for analytical querying
- Executing business-driven SQL queries to generate insights

This project reflects real-world data engineering workflows used in modern analytics teams.

---

## 🧱 Problem Statement

Retail organizations generate large volumes of transactional data across products, customers, and sales channels. However, raw operational data is not optimized for analytical reporting.

This project aims to transform raw retail CSV datasets into a structured, query-efficient data warehouse that enables:

- Fast analytical queries  
- Trend analysis across time periods  
- Revenue breakdown by product and customer segments  
- Scalable reporting infrastructure  

The goal is to bridge the gap between raw operational data and business intelligence.

---

## 🛠️ Tools & Technologies

| Component        | Technology |
|------------------|------------|
| Database         | SQL Server |
| Query Language   | T-SQL |
| Architecture     | Medallion Architecture (Bronze, Silver, Gold) |
| Data Modeling    | Star Schema (Fact & Dimension Tables) |
| Data Source      | CSV Files |
| Version Control  | Git & GitHub |

---

## 📐 Architecture & Design

### 🧱 Medallion Architecture

The warehouse follows a layered Medallion Architecture to progressively refine data quality and usability.

### 🥉 Bronze Layer – Raw Data
- Stores raw retail CSV files
- Minimal transformations applied
- Serves as immutable source layer

### 🥈 Silver Layer – Cleaned & Standardized Data
- Data cleaning and validation
- Standardization of formats and data types
- Deduplication and normalization
- Ensures data consistency before modeling

### 🥇 Gold Layer – Analytics-Ready Model
- Dimensional modeling using Star Schema
- Creation of Fact and Dimension tables
- Optimized for reporting and business queries

This layered approach ensures data quality, maintainability, and scalability.

---

## 📚 Dataset Source

The retail dataset used in this project was obtained from a publicly available SQL Data Warehouse tutorial by Data With Baraa.  
The end-to-end warehouse design, ETL pipelines, dimensional modeling, and documentation were implemented independently to strengthen practical understanding of data engineering concepts.

