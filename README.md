🛒 Walmart Weekly Sales Forecasting

Forecasting weekly sales for Walmart Store 1 using ARIMA, Prophet, and economic indicators like unemployment and CPI.

📌 Problem Statement  
Walmart wants to improve its inventory planning and business strategy by forecasting weekly sales across its U.S. retail stores. This project focuses on Store 1, using time series forecasting models to predict future trends and analyze the impact of external factors like unemployment, temperature, and CPI.

🎯 Objectives  
- Perform Exploratory Data Analysis (EDA) to detect trends, seasonality, and outliers.  
- Analyze the effect of external economic indicators on weekly sales.  
- Build and compare forecasting models: ARIMA, SARIMA, Prophet.  
- Predict the next 12 weeks of sales.  
- Evaluate model performance using RMSE.

🧰 Technologies & Tools  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels (ARIMA/SARIMA)  
- Facebook Prophet  
- Jupyter Notebook

📊 Key Insights  
- Unemployment had strong negative correlation with sales (e.g., Store 44 = −0.80).  
- Holiday periods showed significant drop in weekly sales.  
- CPI and Temperature affected different stores differently.  
- Forecasts helped visualize future sales for planning.

📈 Models Implemented

Model        | Description                         | Evaluation  
------------ | ----------------------------------- | -----------  
ARIMA        | Time series model for trend + noise | RMSE calculated  
SARIMA       | ARIMA with seasonal component       | Suitable for holiday effects  
Prophet      | Facebook's easy-to-use forecasting  | Good handling of seasonality  

📦 Output  
- Forecast for the next 12 weeks  
- Visualizations of trends and seasonal components  
- Model comparison using RMSE

📝 Conclusion  
This project demonstrates how time series forecasting and economic data analysis can help retail companies like Walmart make data-driven inventory and staffing decisions.

📁 Folder Structure  
Walmart_Sales_Forecasting/  
├── Walmart_Weekly_Sales.ipynb  
├── Walmart.csv  
├── Forecast_Plots/  
├── README.md  
└── Report.pdf (optional)

🔗 To Do (Optional Enhancements)  
- [ ] Streamlit deployment for interactive dashboard  
- [ ] Add cross-validation  
- [ ] Expand to all 45 stores

🔗 Connect with me on LinkedIn: [Sushant Kakde]([https://www.linkedin.com/in/sushant-kakde/](https://www.linkedin.com/in/sushant-kakde-21b956325))



