
#🛒 Walmart Weekly Sales Forecasting

##📌 Problem Statement
Walmart wants to improve its inventory planning and business strategy by forecasting weekly sales across its U.S. retail stores. This project focuses on Store 1, using time series forecasting models to predict future sales trends and analyze the impact of external factors like unemployment, temperature, and CPI.

##🎯 Objectives
📊 Perform Exploratory Data Analysis (EDA) to detect trends, seasonality, and outliers.

🔍 Analyze the effect of external economic indicators on weekly sales.

🧠 Build and compare forecasting models like ARIMA, SARIMA, and Facebook Prophet.

📈 Predict the next 12 weeks of sales for Store 1.

⚖️ Choose the best model using performance metrics like RMSE.

##🧰 Technologies & Tools
Python

Pandas, NumPy

Matplotlib, Seaborn

Statsmodels (ARIMA/SARIMA)

Facebook Prophet

Jupyter Notebook

##📊 Key Insights
Unemployment had a strong negative correlation with sales in some stores (e.g., Store 44 = −0.80).

Holiday periods showed significant drop in sales in many cases.

Temperature and CPI showed seasonal and regional variation in impact.

Forecasting models helped estimate sales trend + seasonality, useful for inventory management.

##📈 Models Implemented
Model	Description	Evaluation
ARIMA	Time series model for trend + noise	✅ RMSE calculated
SARIMA	ARIMA with seasonality	✅ Good for holiday effect
Prophet	Business-friendly time series forecasting	✅ Robust to missing data

##📦 Output
✅ Sales forecast for the next 12 weeks for Store 1

✅ Model comparison using RMSE

✅ Visualizations of trend, seasonality, and forecasts

##📝 Conclusion
- This project demonstrates the use of time series forecasting for solving real business problems in retail. It shows how data-driven insights from external variables can be used to improve planning and decision-making in large-scale operations.


---

## 🔗 To Do (Optional Enhancements)
- [ ] Streamlit deployment for interactive dashboard
- [ ] Add cross-validation
- [ ] Expand to all 45 stores

