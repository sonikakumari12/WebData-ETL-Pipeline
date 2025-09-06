WebData ETL Pipeline

* Project Description
WebData ETL Pipeline is a project that collects, processes, and visualizes cryptocurrency data.
The project gathers data from the CoinCap API, transforms it using Python, stores it in a centralized MySQL 
database,and builds interactive dashboards in Power BI.

* Workflow Overview
[CoinCap API] --> [Python Script for Data Transformation] --> [MySQL Database] --> [Power BI Dashboard]

* Stage Details

1.Extract (E)
Fetch data from the CoinCap,
API using Python’s requests library.
Data is returned in JSON format.

2.Transform (T)
Clean, structure, and preprocess the data using Python (pandas).
Perform calculations and formatting to prepare the data for storage and analysis.

3.Load (L)
Store the transformed data in a MySQL database.
Python connects to MySQL using MySQL Connector and SQLAlchemy.
Database provides centralized storage for easy querying.

4.Visualize
Connect MySQL database to Power BI Desktop.
Build dashboards to analyze cryptocurrency trends, performance, and insights.

* Features
Step-by-step ETL process from data extraction to dashboard visualization.
Centralized MySQL database for structured storage.
Interactive Power BI dashboards for data analysis.
Flexible Python scripts for  data transformation.

*Technology Stack
Programming Language: Python
Data Extraction: requests library, CoinCap API
Data Transformation: Python (pandas)
Database: MySQL
Database Connector: MySQL Connector, SQLAlchemy
Data Visualization: Power BI 

*Usage
Run the ETL script to refresh the database.
Use Power BI dashboards to analyze cryptocurrency trends.
Examine top-performing and underperforming coins.

