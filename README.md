# Task-1-FUTURE_DS_01
# Ecommerce Revenue & Product Perfomance Analysis

# Project Overview
This project focuses on analyzing ecommerce transactional data to uncover insights related to:

revenue trends, product performance, category profitability, regional sales performance, customer purchasing behaviour

The project was developed using:
R Programming for data cleaning and preprocessing
Microsoft Power BI for interactive dashboard development and business intelligence visualization

# Background

Ecommerce businesses generate large volumes of transactional data daily. Analyzing this data enables organizations to understand customer purchasing patterns, identify high-performing products, monitor revenue growth, and make data-driven business decisions.

However, raw ecommerce datasets often contain:

cancelled orders, missing customer information, duplicate transactions, inconsistent product descriptions

# Problem Statement
Businesses often struggle to identify:
which products generate the highest revenue, which categories contribute most to profitability, which regions perform best, how revenue changes over time

Without proper analysis, decision-makers may fail to:
optimize inventory, prioritize profitable product categories, improve marketing strategies, identify sales growth opportunities
This project addresses these challenges through data cleaning, exploratory analysis, and dashboard visualization.

# AIM
The aim of this project is to analyze ecommerce order data in order to identify revenue trends, high-performing products, profitable categories, and regional sales performance using business intelligence techniques.

# Research Questions
This project aims to answer the following questions:
How does revenue change over time?, Which products generate the highest sales revenue?, Which products are sold most frequently?, Which product categories contribute the most revenue, Which countries or regions are the most profitable?, What business insights can be derived from ecommerce sales trends?

# Data Cleaning & Preparation
Data cleaning was performed using R Programming.

The following preprocessing steps were completed:

Removed cancelled transactions from revenue analysis, Replaced missing customer IDs with "Unknown Customer", Removed duplicate transactions, Converted invoice dates into datetime format, Created sales revenue variable, Extracted month and year variables, Standardized product descriptions, Engineered product categories from descriptions

Revenue calculation:
Sales=Quantity×UnitPrice

# Key Graphs & Visualizations
| Visualization                                  | Purpose                       |
| ---------------------------------------------- | ----------------------------- |
| KPI Cards                                      | Summary business metrics      |
| Monthly Revenue Trend                          | Revenue growth analysis       |
| Monthly Orders Trend                           | Order activity analysis       |
| Top Selling Products Bar Chart                 | Product demand analysis       |
| Revenue Contribution by Category (Donut Chart) | Category profitability        |
| Revenue by Country Chart                       | Regional performance analysis |

# Dashboard Insights

Key insights identified from the analysis include:
Revenue demonstrates strong monthly growth trends, A small number of products contribute significantly to total sales, Certain product categories dominate overall revenue contribution, Some countries generate substantially higher revenue than others, Seasonal purchasing patterns are visible across monthly sales trends.

# Tools & Technologies Used
| Tool          | Purpose                         |
| ------------- | ------------------------------- |
| R Programming | Data cleaning and preprocessing |
| Tidyverse     | Data transformation             |
| Lubridate     | Date manipulation               |
| Power BI      | Dashboard development           |
| Excel         | Data inspection and validation  |

# Conclusion 
This project demonstrates how ecommerce transactional data can be transformed into meaningful business insights using data analytics and business intelligence tools.

The analysis successfully identified:
revenue trends, top-selling products, profitable categories,strong-performing regions

The interactive Power BI dashboard provides decision-makers with a clear and simplified view of business performance, enabling more informed strategic decisions related to inventory management, marketing, and revenue growth.

Data
https://www.kaggle.com/datasets/carrie1/ecommerce-data
