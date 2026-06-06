# Retail-Sales-Analysis-Using-PySpark
Big Data Analytics project using PySpark to analyze 541,909 retail transactions and discover sales trends, country-wise distribution, missing values, and transaction patterns.
# Retail Sales Analysis Using PySpark

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a large-scale international retail dataset using PySpark. The dataset contains 541,909 retail transactions collected from an online retail store. The goal is to identify sales patterns, transaction trends, country-wise distribution, and data quality issues using Big Data Analytics techniques.

## Objectives
- Analyze large retail transaction data using PySpark
- Perform data cleaning and preprocessing
- Identify missing values and outliers
- Analyze transaction trends over time
- Study country-wise sales distribution
- Generate meaningful business insights through visualization

## Dataset Information
## Dataset

The dataset used in this project is available through Google Drive.

### Download Dataset
https://drive.google.com/file/d/1kHzc6CeRv4_-C7GChJqrcj8PbCvqHt4H/view?usp=sharing

### Dataset Information
- Dataset Name: Online Retail Dataset
- Total Records: 541,909
- Total Features: 8
- Format: CSV

### Features
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

### Original Source
UCI Machine Learning Repository – Online Retail Dataset

### Dataset Attributes
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Technologies Used
- Python
- PySpark
- Pandas
- NumPy
- Matplotlib

## Project Workflow

### 1. Data Loading
- Created Spark Session
- Loaded CSV dataset using PySpark

### 2. Data Preprocessing
- Handled missing values
- Standardized country names
- Converted data types
- Created Amount column

### 3. Exploratory Data Analysis
- Summary statistics
- Missing value analysis
- Country-wise transaction analysis
- Daily transaction analysis
- Monthly transaction analysis

### 4. Data Visualization
- Monthly transaction trends
- Daily transaction trends
- Country distribution pie chart
- Non-null value analysis chart

## Key Findings
- United Kingdom dominates overall transactions.
- CustomerID contains significant missing values.
- Strong seasonal sales patterns were observed.
- Monthly transactions peak during holiday periods.
- Transaction volume varies significantly across countries.

## Results
- Processed over 541K retail records using PySpark.
- Generated transaction trend visualizations.
- Identified geographic concentration of sales.
- Derived business insights for decision making.

## Future Enhancements
- Customer Segmentation using RFM Analysis
- Demand Forecasting
- Spark MLlib Integration
- Real-Time Analytics Dashboard
- Cloud Deployment using Databricks or AWS

## Authors
- Harsha Gowda S
- Gireesh G Koppad

## Academic Information
Big Data Analytics Lab Project  
School of Computer Science and Engineering  
REVA University

