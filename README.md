# Retail Sales Performance Dashboard 📊

An end-to-end data processing and visualization project built with Python. This project takes messy retail sales data, applies advanced data cleaning and imputation techniques, and generates a professional, multi-plot dashboard focusing on the most recent 3 months of sales performance.

## 🧹 Data Cleaning & Preprocessing

The original dataset contained missing and inconsistent values. To ensure accurate analysis, the following data wrangling techniques were applied using Pandas:

- **Cross-Imputation:** Missing numerical values across `Price Per Unit`, `Quantity`, and `Total Spent` were calculated and imputed by leveraging the mathematical relationship between the three columns (e.g., Total Spent = Price Per Unit × Quantity).
- **Reference Lookups:** Missing `Item` names were dynamically reconstructed and filled by looking up exact matches based on known `Price Per Unit` and `Category` pairings.

## 🎯 Dashboard Features

- **Time-Series Filtering:** Automatically filters the dataset to a rolling 90-day window to analyze recent trends.
- **Revenue by Category:** Bar chart visualizing total spend across different product categories (Food, Patisserie, Butchers, etc.).
- **Sales Trend Analysis:** Time-series line plot tracking daily aggregate revenue over the 3-month period.
- **Transaction Insights:** Count plot comparing payment method preferences (Digital Wallet, Cash, Credit Card) across In-Store and Online channels.
- **Discount Impact:** Boxplot distribution illustrating how applied discounts affect total customer spend per category.

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas:** Data manipulation, advanced missing value imputation, lookups, and time-series aggregation.
- **Matplotlib & Seaborn:** Advanced data visualization and dashboard grid layout construction.

## 📂 Dataset

The raw data for this project originated from Kaggle:
[Retail Store Sales - Dirty for Data Cleaning](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning) provided by Ahmed Mohamed.

_(Note: Ensure the fully cleaned dataset is named `cleaned_retail_store_sales.csv` and placed in the root directory before running the dashboard script)._

## 🚀 Getting Started

### 1. Clone the repository

Open your terminal and run:

```bash
git clone https://github.com/Makhall/retail-sales-dashboard.git
cd retail-sales-dashboard
```
