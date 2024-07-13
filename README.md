# Demand Forecasting Research Project:
---------

## Objective:
- This projects aims to create forecasting model for the sales data.

## Approach:
- **Performed an exhaustive EDA on the dataset.**
    - To understand the data, and look for potential features having high importance.
    - To identify the target variable.
    - ***Notebooks***:
        - Overall at Segment Level
        - Categorising Timeseries into Ongoing, Discontinued and Newly Launched items.
        - In depth analysis of timeseries for an item, looking for stationarity, trends, seasonality.
- **Creating Forecasting model.**
    - ***Notebooks***:
        - ARIMA and SARIMA
        - VARMAX
            - To created VARMAX model we need to have endogeneous and exogenous variables.
            - To determine the exogeneous variable, I ran ***Granger Causality Test*** over item data for a segment.
            - Once, exogeneous and endogeneous variables are defined. I trained and forecasted timeseries using VARMAX model.