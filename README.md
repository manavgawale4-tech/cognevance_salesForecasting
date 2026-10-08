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
├── Dataset/
│   ├── stores_sales_forecasting.csv
│   ├── monthly_sales_cleaned.csv
│   └── future_sales_forecast.csv
│
├── notebook/
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
4. Aggregate sales data by month and year.
5. Analyze monthly and yearly sales trends.
6. Create visualizations.
7. Create a time index for forecasting.
8. Train a Linear Regression model.
9. Evaluate the model using MAE, RMSE and R² Score.
10. Forecast sales for the next 12 months.

## Model Performance

| Metric   |   Value |
| -------- | ------: |
| MAE      | 6655.95 |
| RMSE     | 8272.27 |
| R² Score |   0.157 |

The simple Linear Regression model captures the overall trend but has limited predictive performance because only time was used as the input feature.

## Key Insights

* Yearly sales increased from 2014 to 2017.
* November 2017 recorded the highest monthly sales.
* February 2014 recorded the lowest monthly sales.
* Historical sales show fluctuations across different months.
* Linear Regression provides a basic trend-based forecast.
* Advanced time-series models could improve forecasting accuracy.

## Visualizations

The project contains visualizations for:

* Monthly Sales Trend
* Yearly Sales Trend
* Actual vs Predicted Sales
* Actual Sales vs Forecasted Sales

## Future Improvements

The project can be improved by:

* Adding seasonal features.
* Using multiple business-related features.
* Applying advanced time-series models.
* Comparing multiple forecasting algorithms.
* Creating an interactive dashboard using Power BI or Tableau.

## Internship

This project was completed as part of the **Data Analytics & Data Science Internship at Cognevance Technologies**.
