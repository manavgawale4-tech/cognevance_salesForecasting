# Sales Forecasting System

## 1. Project Overview

This project focuses on analyzing historical sales data and forecasting future sales using Python and Linear Regression.

The project was completed as part of the Cognevance Technologies internship.

## 2. Dataset

The dataset used for this project is a Superstore sales dataset containing historical order and sales information.

* Total Records: 2,121
* Total Columns: 21
* Sales data analyzed on a monthly and yearly basis
* Target variable: Sales

## 3. Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Loaded the dataset using Pandas.
* Handled the file encoding issue using Latin-1 encoding.
* Checked for missing values.
* Checked for duplicate records.
* Converted the `Order Date` column into datetime format.
* Aggregated sales data on a monthly basis.
* Created a `Time_Index` column for the forecasting model.

No missing values or duplicate records were found in the dataset.

## 4. Sales Trend Analysis

Monthly sales were analyzed to identify changes and trends over time.

### Yearly Total Sales

| Year | Total Sales |
| ---- | ----------: |
| 2014 |  157,192.85 |
| 2015 |  170,518.24 |
| 2016 |  198,901.44 |
| 2017 |  215,387.27 |

The highest monthly sales were recorded in November 2017, while the lowest monthly sales were recorded in February 2014.

## 5. Forecasting Model

Linear Regression was used to forecast future sales.

* Input Feature: `Time_Index`
* Target Variable: `Sales`
* Algorithm: Linear Regression

The model was trained using historical monthly sales data.

## 6. Model Evaluation

The model performance was evaluated using MAE, RMSE and R² Score.

| Metric   |   Value |
| -------- | ------: |
| MAE      | 6655.95 |
| RMSE     | 8272.27 |
| R² Score |   0.157 |

The R² score indicates that a simple time-based Linear Regression model explains only a limited portion of the variation in monthly sales. This is because sales can be affected by seasonal patterns and other business factors that were not included in this simple model.

## 7. Sales Forecast

The trained Linear Regression model was used to forecast sales for the next 12 months.

The forecast was generated using future `Time_Index` values and the trained model.

The forecast provides a basic trend-based estimate of future sales.

## 8. Visualizations

The project includes the following visualizations:

* Monthly Sales Trend
* Yearly Sales Trend
* Actual vs Predicted Sales
* Actual Sales vs Forecasted Sales

These visualizations help understand historical sales patterns and the model's forecast.

## 9. Key Insights

* Yearly sales increased from 2014 to 2017.
* November 2017 recorded the highest monthly sales.
* February 2014 recorded the lowest monthly sales.
* The Linear Regression model identifies the overall sales trend.
* The model has limited predictive performance because only time was used as the input feature.
* More advanced forecasting methods could improve prediction accuracy.

## 10. Conclusion

This project demonstrates a basic sales forecasting workflow using Python, Pandas, Matplotlib and Scikit-learn.

The workflow includes data loading, preprocessing, monthly and yearly sales analysis, visualization, Linear Regression modeling, model evaluation and future sales forecasting.

The project can be further improved by using additional features and advanced time-series forecasting techniques.
