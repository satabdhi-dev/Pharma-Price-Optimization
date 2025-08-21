# Pharma Price Optimization Using Python

## Project Overview

The **Pharma Price Optimization** project aims to help pharmaceutical companies make data-driven decisions to maximize revenue and market competitiveness. By analyzing historical sales, market trends, and pricing patterns, this project builds predictive models to suggest optimal pricing strategies for products.

## Key Features

* **Data Analysis:** Exploratory analysis of pharmaceutical sales, prices, and market trends.
* **Price Prediction Models:** Implemented regression-based models to forecast optimal prices.
* **Optimization Algorithm:** Identifies price points that maximize revenue while considering market constraints.
* **Visualization:** Interactive charts to understand pricing trends and model predictions.

## Technologies & Tools

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
* **Optimization:** Linear Programming, Regression Models
* **Environment:** Jupyter Notebook

## Dataset

The dataset used includes historical sales, product information, and pricing details.

**Source:** \[https://1drv.ms/x/c/5567dd28f0ce5710/EWC4atMG25dLpTbk6Pus30QB4cVmF9T-Go5xao2SyB7gpg?e=kanN7v]

**Dataset Features:**

* `Product_ID`: Unique identifier for each pharmaceutical product
* `Price`: Historical product price
* `Sales`: Units sold
* `Market_Share`: Market share of the product
* `Competitor_Price`: Competitor pricing for similar products
* `Date`: Sales and pricing timestamp

## Methodology

1. **Data Cleaning & Preprocessing:** Handled missing values, outliers, and feature engineering.
2. **Exploratory Data Analysis (EDA):** Identified trends, correlations, and seasonal patterns.
3. **Model Development:**

   * Linear Regression
   * Random Forest Regressor
   * XGBoost Regressor
4. **Price Optimization:**

   * Applied predictive models to forecast revenue for multiple price points.
   * Selected the price that maximizes revenue while maintaining market competitiveness.
5. **Evaluation:**

   * Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), R² Score

## Results

* Predicted optimal price points for all products with accuracy metrics:

  * MAE: 1084.29
  * RMSE: 1535.99
  * R² Score: 1.00

* Interactive visualizations for pricing strategy and sales impact.

## Future Work

* Integrate competitor dynamics in real-time using API data.
* Extend the model to include multi-country pricing optimization.
* Deploy as a web application/dashboard for business users.

## Project Impact

This project demonstrates how data-driven strategies can optimize pharmaceutical pricing, improve revenue, and enhance market competitiveness. It is suitable for roles in **data analytics, business intelligence, and revenue management**.
