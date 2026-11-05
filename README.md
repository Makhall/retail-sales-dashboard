# Retail Sales Performance Dashboard 📊

An end-to-end data processing and visualization project built with Python. This project takes retail sales data, processes it, and generates a professional, multi-plot dashboard focusing on the most recent 3 months of sales performance.

## 🎯 Project Features

- **Time-Series Filtering:** Automatically filters the dataset to a rolling 90-day window to analyze the most recent trends.
- **Revenue by Category:** Bar chart visualizing total spend across different product categories (Food, Patisserie, Butchers, etc.).
- **Sales Trend Analysis:** Time-series line plot tracking daily aggregate revenue over the 3-month period.
- **Transaction Insights:** Count plot comparing payment method preferences (Digital Wallet, Cash, Credit Card) across In-Store and Online channels.
- **Discount Impact:** Boxplot distribution illustrating how applied discounts affect total customer spend per category.

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas:** Data manipulation, cleaning, filtering, and time-series aggregation.
- **Matplotlib & Seaborn:** Advanced data visualization and dashboard grid layout construction.

## 📂 Dataset

The data for this project originated from Kaggle:
[Retail Store Sales - Dirty for Data Cleaning](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning) provided by Ahmed Mohamed.

The raw data was cleaned and transformed before being loaded into this dashboard. _(Note: Ensure the dataset is named `cleaned_retail_store_sales.csv` and placed in the root directory before running the script)._

## 🚀 Getting Started

### 1. Clone the repository

Open your terminal and run:

```bash
git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
cd YOUR-REPO-NAME
```
