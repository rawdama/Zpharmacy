# Pharmacy Sales Dashboard

## Project Overview

The goal of this project is to analyze and visualize daily sales data for a pharmacy. This dashboard provides insights into various metrics such as total sales, profit, client statistics, and category performance.

## Features

- **Daily Sales Summary**: Displays total sales, profit, and client counts.
- **Category Breakdown**: Insights into sales and profits by category.
- **Traffic Analysis**: Hourly sales traffic analysis to identify peak times.
- **Top Contributors**: Highlights the top products contributing to sales.
- **Slicers**: Interactive filters for year, month, and day to customize data views.

## Data Source

The data is stored in a SQL Server database. The structure includes tables for sales transactions, product categories, and client information.

### Database Setup

1. **Prerequisites**:
   - SQL Server installed and running.
   - Access to SQL Server Management Studio (SSMS).

2. **Importing Data**:
   - Run the provided `.bac` file in your SQL Server to set up the necessary database and tables.

## Dashboard Overview

The dashboard contains the following key sections:

- **Sales Metrics**: 
  - Total daily sales: **213.78K**
  - Total profit: **67.66K**
  - Client count: **56** (Number of clients)

- **Sales Trends**: 
  - Sales decreased by **10%**.
  - Cost decreased by **10%**.

- **Category Performance**: 
  - Detailed breakdown of sales by product category.

- **Traffic Analysis**: 
  - Hourly analysis of sales traffic to optimize staffing and inventory.

- **Slicers**: 
  - The dashboard includes slicers for **Year**, **Month**, and **Day** to filter data dynamically, allowing users to view sales metrics over different time periods.

- **Payment Type Analysis**: 
  - A donut chart visualizes total sales by each payment type, providing insights into customer payment preferences.
