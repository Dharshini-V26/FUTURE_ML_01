# AI-Powered Sales Forecasting Dashboard
An end-to-end sales forecasting and business intelligence project that applies time series forecasting using Facebook Prophet and presents insights through an interactive Power BI dashboard. This project helps retail businesses understand historical trends, forecast future sales, and make data-driven decisions.

## Project Overview
Retail organizations rely heavily on accurate sales forecasts for inventory planning, marketing strategies, and revenue optimization.
This project combines machine learning, data analysis, and visualization to:
1) Analyze historical sales data
2) Forecast future sales trends using a time series model
3) Visualize insights through an interactive dashboard

## Objectives
1) Forecast future sales using historical retail data
2) Compare actual vs predicted sales trends
3) Identify top-performing categories and sub-categories
4) Analyze profit contributions and regional performance
5) Present insights in a professional Power BI dashboard

## Machine Learning Approach
### Model Used: Facebook Prophet
Prophet is a robust time series forecasting model developed by Meta that is especially effective for business data.
### Why Prophet?
1) Handles seasonality and trends automatically
2) Works well with missing values
3) Requires minimal tuning
4) Ideal for daily, weekly, and monthly sales data

## Forecasting Workflow
### Data Cleaning & Preparation
1) Converted order dates to datetime format
2) Aggregated sales data at a daily level
3) Renamed columns to Prophet format (ds,y)
### Model Training
1) Initialized Prophet model
2) Fitted the model on historical sales data
### Future Prediction
1) Generated future dates
2) Forecasted upcoming sales
3) Extracted predicted values and confidence intervals
### Evaluation
1) Compared actual vs forecasted sales
2) Calculated performance metrics (MAE, RMSE)
### Export for BI
1) Saved forecast results as "sales_forecast.csv"
2) Integrated predictions into Power BI

## Power BI Dashboard Features
### Key Visualizations
1) Actual vs Forecasted Sales Trend (Line Chart)
2) Sales & Profit Comparison by Category
3) Profit Contribution Breakdown (Waterfall Chart)
4) Sales Distribution by Category & Sub-Category (Tree Map)
5) Sales & Profit by State (Map)
6) Sales Share by Category (Donut Chart)
### KPI Cards
1) Total Sales
2) Total Profit
3) Total Orders
4) Average Sales per Order
