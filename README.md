# Sales Forecasting System

A sales forecasting project developed using Python, Pandas, Matplotlib, and Scikit-learn as part of the Cognevance Technologies internship.

## Project Overview

This project analyzes historical sales data and uses Linear Regression to forecast future sales.

The project includes data preprocessing, monthly and yearly sales analysis, visualization, model evaluation, and 12-month sales forecasting.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses a Superstore sales dataset containing historical sales and order information.

* Records: 2,121
* Columns: 21
* Target Variable: Sales

## Project Structure

```text
cognevance_salesForecasting/
│
├── dataset/
│   ├── stores_sales_forecasting.csv
│   ├── monthly_sales_cleaned.csv
│   └── future_sales_forecast.csv
│
├── notebooks/
│   └── sales_forecasting_analysis.ipynb
│
├── Visualizations/
│   ├── monthly_sales_trend.png
│   ├── yearly_sales_trend.png
│   ├── actual_vs_predicted_sales.png
│   └── sales_forecast.png
│
├── report/
│   └── Sales_Forecasting_Report.md
│
└── README.md
```

## Workflow

1. Load the sales dataset.
2. Check missing values and duplicate records.
3. Convert order dates into datetime format.
4. Aggregate sales data by
