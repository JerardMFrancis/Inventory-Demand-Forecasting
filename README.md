# Inventory Demand Forecasting

## Overview

This project focuses on forecasting inventory demand using historical retail transaction data. It includes data preprocessing, exploratory data analysis (EDA), time series analysis, and demand forecasting using the ARIMA model. The project helps identify sales trends and predict future demand to support inventory planning and decision-making.

---

## Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Daily Sales Trend Analysis
- 7-Day Rolling Average Visualization
- Top 10 Customers by Spending Analysis
- Time Series Forecasting using ARIMA
- Forecast Visualization
- Model Evaluation (MAE, RMSE, R² Score)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

---

## Project Structure

```
Inventory-Demand-Forecasting/
│
├── notebooks/
│   └── Inventory_Demand_Forecasting.ipynb
│
├── data/
│   └── retail_transactions.csv
│
├── images/
│   ├── daily_sales_trend.png
│   ├── daily_sales_trend_7day_rolling_average.png
│   ├── arima_sales_forecast.png
│   └── top10_customers_by_spending.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Inventory-Demand-Forecasting.git
```

Navigate to the project folder:

```bash
cd Inventory-Demand-Forecasting
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and run all cells.

---

## Visualizations

### Daily Sales Trend

![Daily Sales Trend](images/daily_sales_trend.png)

### Daily Sales Trend with 7-Day Rolling Average

![Rolling Average](images/daily_sales_trend_7day_rolling_average.png)

### ARIMA Sales Forecast

![ARIMA Forecast](images/arima_sales_forecast.png)

### Top 10 Customers by Spending

![Top Customers](images/top10_customers_by_spending.png)

---

## Results

- Analyzed historical sales trends using exploratory data analysis.
- Applied ARIMA for inventory demand forecasting.
- Compared forecasted values with historical sales data.
- Evaluated forecasting performance using MAE, RMSE, and R² Score.

---

## Future Improvements

- Compare ARIMA with advanced forecasting models such as Prophet, XGBoost, and LSTM.
- Develop an interactive dashboard for real-time demand analysis.
- Automate periodic inventory demand forecasting.

---

## Author

**Jerard M Francis**

B.Tech CSE (Data Science & Machine Learning)

LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN

GitHub: https://github.com/YOUR_USERNAME

---
