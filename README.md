# Data Engineering Project

## Project Overview
This project focuses on designing, building, and analyzing a data architecture for a sales-based dataset. We started with the database design in SQL Server, followed by data analysis in SQL, exploratory data analysis (EDA) and forecasting in Python, and ultimately data warehousing in Azure Synapse Analytics.

## Project Steps

### 1. Database Design and ERD Modeling
   - Created a relational database in SQL Server.
   - Designed the Entity-Relationship Diagram (ERD) to visually map out the database structure and relationships.
   - **ERD Image**: <img src="https://github.com/AhmedAboelkasem/Amazon-Sales/blob/main/ERD%20image.png?raw=true">

### 2. Data Analysis in SQL
   - Conducted analysis using SQL queries on the raw data to gain initial insights into sales patterns, trends, and customer behavior.
   
### 3. Exploratory Data Analysis (EDA) and Sales Forecasting in Python
   - Performed EDA on the dataset to understand distributions, correlations, and data quality.
   - Built a sales forecasting model in Python to predict future sales trends based on historical data.

### 4. Data Warehousing and ETL with Snowflake Schema
   - Designed and implemented a data warehouse using the Snowflake schema model.
   - Developed an ETL pipeline in Python to extract data from SQL Server, perform necessary transformations, and load the processed data as CSV files.
   - Uploaded CSV files to a dedicated SQL pool (data warehouse) in Azure Synapse Analytics for centralized data storage and advanced analytics.

### 5. Loading Data into Azure Synapse Analytics
   - Loaded CSV files into the dedicated SQL pool in Microsoft Azure, setting up a scalable environment for reporting, analytics, and future integrations.

