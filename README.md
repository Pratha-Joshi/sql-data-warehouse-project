# Data Warehouse and Analytics Project 
Building a modern data warehouse with SQL server, including ETL processes, data modeling, and analytics.

The data architecture follows Medallion Architecture. The Bronze Layer stores raw data as-is from the source system. The data is ingested from CSV files into SQL server database. In the Silver Layer, data cleansing, standardization, and normalization processes are involved to prepare data for analysis. The Gold Layer houses business-ready data modeled into a star schema required for reporting and analytics.
