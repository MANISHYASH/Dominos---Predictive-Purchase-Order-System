# Dominos---Predictive-Purchase-Order-System

This project focuses on analyzing pizza sales data and performing time series forecasting using models like ARIMA, SARIMAX, and Prophet. The analysis includes exploring pizza ingredients and their impact on sales, as well as visualizing trends and making future predictions.

Overview
--------
The project covers:

- Pizza Sales Analysis: Analysis of pizza sales trends over time.
- Ingredient Analysis: Exploration of pizza ingredients and their impact on sales.
- Time Series Forecasting: Using ARIMA, SARIMAX, and Prophet models to predict future pizza sales.
- Visualizations: Providing clear visual insights into the data using Python plotting libraries.

Raw Datasets
------------
Two datasets are included in the project:

1. Pizza_Sale.xlsx: Contains historical pizza sales data.
2. Pizza_ingredients.xlsx: Contains data about the ingredients used in the pizzas.

Dataset Details
---------------
1. Pizza_Sale.xlsx
  - pizza_id: Unique identifier for each pizza.
  - order_id: Unique identifier for each order.
  - pizza_name_id: Identifier linking the pizza to its name.
  - quantity: Number of pizzas ordered.
  - order_date: Date when the order was placed.
  - order_time: Time when the order was placed.
  - unit_price: Price of a single pizza unit.
  - total_price: Total price for the ordered quantity.
  - pizza_size: Size of the pizza (e.g., small, medium, large).
  - pizza_category: Category of the pizza (e.g., vegetarian, non-vegetarian).
  - pizza_ingredients: Ingredients used in the pizza.
  - pizza_name: Name of the pizza.

2. Pizza_ingredients.xlsx
  - pizza_name_id: Identifier linking to the pizza name.
  - pizza_name: Name of the pizza.
  - pizza_ingredients: List of ingredients used in the pizza.
  - Items_Qty_In_Grams: Quantity of each ingredient in grams.

Libraries Used
--------------
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- Prophet (by Facebook)
- scikit-learn
- squarify (for tree maps)
- itertools
- holidays (for handling special date considerations)

Notebooks Overview
------------------
- DC_EDA_MODEL.ipynb: This notebook performs the analysis on the pizza sales and ingredients data. It includes:
Data cleaning and preprocessing.
- Exploratory data analysis (EDA) of pizza sales and ingredients.
- Time series decomposition of pizza sales data.
- Building ARIMA, SARIMAX, and Prophet models for sales forecasting.
- Model evaluation using metrics like MAPE (Mean Absolute Percentage Error).

Results
-------
The notebook demonstrates:

- Sales trends, seasonality, and important ingredients influencing sales.
- Time series models (ARIMA, SARIMAX, Prophet) for predicting future pizza sales.
- Visualizations to highlight data patterns and model predictions.

Contact
---------
For any questions or inquiries regarding this project, feel free to contact:

Email: yashwantmanish@gmail.com
LinkedIn: https://www.linkedin.com/in/manish-yashwant/
