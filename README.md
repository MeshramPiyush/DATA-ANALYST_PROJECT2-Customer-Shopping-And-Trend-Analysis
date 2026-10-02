# Customer Shopping Behavior Analysis
Data Analysis Project using Python ,Sql, Powerbi, Excel

## 📌 Overview

This project analyzes customer shopping behavior using a dataset of 3,900 customer purchase records.

The project follows an end-to-end data analytics workflow:

**CSV Dataset → Python → SQL Server → Power BI → Project Report → Presentation**

The goal is to identify customer purchasing patterns, spending behavior, product preferences, customer segments, subscription behavior, and other business insights.

## 📊 Dataset

The dataset contains 3,900 records and 18 columns covering:

- Customer demographics
- Product and purchase details
- Review ratings
- Discounts
- Subscription status
- Previous purchases
- Purchase frequency
- Shipping and payment information

## 🛠️ Tools Used

- **Python** – Data cleaning, EDA and feature engineering
- **Pandas** – Data manipulation
- **Microsoft SQL Server** – Data storage and SQL analysis
- **SSMS** – SQL database management and query execution
- **Power BI** – Interactive dashboard and visualization
- **Gamma** – Project presentation
- **GitHub** – Project documentation and version control

## 🔄 Project Workflow

### 1. Python

Loaded the CSV dataset into Jupyter Notebook and performed:

- Exploratory Data Analysis (EDA)
- Data cleaning
- Missing value handling
- Column standardization
- Feature engineering

### 2. SQL Server

The cleaned data was uploaded from Python to Microsoft SQL Server.

SQL queries were used to analyze:

- Revenue
- Customer segments
- Product performance
- Discounts
- Subscription behavior
- Repeat customers
- Age-group revenue

### 3. Power BI

The SQL Server data was connected to Power BI to create an interactive dashboard showing customer and sales insights.

### 4. Report & Presentation

A detailed project report was created along with a presentation using Gamma to communicate the findings and business recommendations.

## 📈 Dashboard

The Power BI dashboard provides visual insights into:

- Customer demographics
- Revenue
- Product performance
- Customer segments
- Subscription behavior
- Discounts
- Purchase patterns

## 💡 Key Results

The analysis provides insights into customer spending, product performance, customer loyalty, discount usage, subscription behavior, and revenue contribution across different customer groups.

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── SQL/
│   └── Customer_Shopping_Behavior_Analysis.sql
│
├── PowerBI/
│   └── Customer_Shopping_Behavior_Dashboard.pbix
│
├── Report/
│   └── Customer_Shopping_Behavior_Project_Report.pdf
│
├── Presentation/
│   └── Customer_Shopping_Behavior_Presentation.pdf
│
└── README.md
