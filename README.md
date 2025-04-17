# stock-price-forecasting
Forecasting Netflix and Amazon stock prices using exponential smoothing, moving averages, linear trends, and regression models. Includes MAPE analysis and baseline comparison.
Stock Price Forecasting: Netflix (NFLX) & Amazon (AMZN)

This project explores the forecasting of stock prices for Netflix (NFLX) and Amazon (AMZN) using both short-term and long-term statistical models. Through time series forecasting techniques and regression analysis, the study aims to provide accurate price predictions and evaluate model effectiveness using MAPE.

---

##  Objectives
- Analyze one year of historical stock data (252 trading days) for NFLX and AMZN
- Apply exponential smoothing, adjusted smoothing, moving averages, and regression models
- Compare model accuracy using MAPE and evaluate performance against a baseline
- Recommend optimal forecasting strategies to guide investment decisions

---

##  Forecasting Techniques

###  Part 1: Short-Term Forecasting
- **Exponential Smoothing** with α = 0.30, 0.45, 0.60, 0.75
- **Adjusted Exponential Smoothing** with trend (β)
- **Adjacent Exponential Smoothing** for dynamic changes

###  Part 2: Long-Term Forecasting
- **3-Period Weighted Moving Average**
- **Linear Trend Analysis** for periods beyond 50
- MAPE calculated for performance comparison

###  Part 3: Regression Modeling
- Simple linear regression on time series
- Residual analysis for validation
- MAPE used for model accuracy

###  Part 4: Baseline Model
- Predicts current price using the most recent period value
- Serves as a benchmark for evaluating advanced models

---

##  Tools Used
- Microsoft Excel for calculations and visualizations
- Statistical methods: Exponential Smoothing, Regression, Moving Averages
- MAPE for forecast accuracy comparison

---

##  Files Included
- `Stock_Price_Forecasting.xlsx`: Forecast models, visualizations, and calculations
- `Stock_Price_Forecasting_Report.docx`: Written summary of analysis, methods, and results
- `README.md`: Overview of the project and methodology

---

##  Key Takeaways
- Adjusted exponential smoothing improved short-term accuracy
- Regression analysis validated price trends over time
- MAPE helped identify the best-performing models
- Baseline comparisons provided practical insight into real-world model usefulness

---

This project demonstrates how time series forecasting techniques can be applied to financial markets to assist investors and analysts in making informed stock-related decisions.
