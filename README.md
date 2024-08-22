# Athletic Sales Analysis - Jupyter Notebook

## Overview

This Jupyter notebook provides an in-depth analysis of athletic sales data from the years 2020 and 2021. The goal of this analysis is to identify trends, assess performance across different regions and product categories, and generate insights that can help improve business strategies in the athletic retail sector.

## Dataset Information

The analysis is based on two CSV files containing sales data:
1.	athletic_sales_2020.csv: Contains sales data for the year 2020.
2.	athletic_sales_2021.csv: Contains sales data for the year 2021.

### Columns in the Dataset:

- retailer: Name of the retail chain.
- retailer_id: Unique identifier for the retailer.
- invoice_date: Date of the transaction.
- region: Geographical region where the sale occurred (e.g., Northeast, Midwest).
- state: U.S. state where the sale occurred.
- city: City where the sale occurred.
- product: Category of the product sold (e.g., Men’s Street Footwear, Women’s Apparel).
- price_per_unit: Price per unit of the product sold.
- units_sold: Number of units sold.
- total_sales: Total sales amount for the transaction.
- operating_profit: Profit made from the sale.
- sales_method: Sales channel used (e.g., In-store, Online, Outlet).

## Notebook Contents

### Data Loading

1. Loading the CSV files into pandas DataFrames.
2. Initial examination of the data structure and summary statistics.
3. Combination of the sales data by rows. 

### Exploratory Data Analysis (EDA)

Exploration of sales trends over time, by region, state, and city.

### Comparative Analysis (2020 vs. 2021)

Comparing sales performance between 2020 and 2021. <br>
Identifying significant changes in sales volume, revenue, and profit margins.

## Dependencies

Pandas Python library for data manipulation and analysis.

## How to Run

1. Ensure that the necessary Python libraries are installed.
2. Place the Resources folder with the athletic_sales_2020.csv and athletic_sales_2021.csv files in the same directory as the notebook.
3. Open the notebook in Jupyter and run the cells sequentially.

