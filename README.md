# Interactive Sales Dashboard

## Overview
This project creates an **interactive sales dashboard** to visualize and analyze sales performance across regions, product categories, and time periods. It uses Python, Pandas, and Plotly to provide insights through KPIs and interactive visualizations.

The dataset is loaded directly from a **public GitHub repository**, which avoids manual downloads or Kaggle API issues.  

## Dataset
Dataset used: Superstore dataset (US)  
[GitHub Dataset Link](https://github.com/leonism/sample-superstore/blob/master/data/superstore.csv)

**Key Columns:**
- Order ID
- Product Name
- Category
- Sub-Category
- Sales
- Profit
- Region
- Order Date

## Features
- Interactive dashboard with filters for **Region** and **Product Category**
- Key Performance Indicators (KPIs): Total Sales, Total Profit, Total Orders
- Visualizations:
  - Revenue by Region
  - Top 10 Products by Sales
- Fully automated data loading from GitHub — no manual upload required

## Methodology
1. **Data Loading:** Load dataset directly from GitHub using pandas.  
2. **Data Preprocessing:** Parse dates, clean data, create new columns for analysis.  
3. **Exploratory Data Analysis (EDA):** Calculate KPIs, summarize sales, profits, and orders.  
4. **Interactive Dashboard:** Built with Plotly and ipywidgets for filtering by region and product category.  

## How to Run
1. Clone the repository.  
2. Open the notebook in **Google Colab**.  
3. Run all cells — the dataset will be loaded automatically, and the dashboard will be interactive.  

## Libraries Used
- pandas  
- plotly  
- ipywidgets  
