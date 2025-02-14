# Times_Series_Studies


---

# **Time Series Forecasting with ARIMA and SARIMAX**  

This repository contains two time series forecasting projects using **Statsmodels**, demonstrating the application of **ARIMA** and **SARIMAX (SARIMA)** models for real-world datasets.  

## **Projects Overview**  

### **1️⃣ ARIMA: World Population Forecasting**  
📌 **Dataset:** [World Population Growth](https://www.kaggle.com/datasets/maheshmani13/world-population-growth/data)  
📈 **Objective:** Forecast global population trends based on historical data.  
🔧 **Approach:**  
- Used **ARIMA (AutoRegressive Integrated Moving Average)** to model and predict population growth.  
- Performed **stationarity tests (ADF test)** and **differencing** to stabilize the time series.  
- Tuned ARIMA hyperparameters **(p, d, q)** to optimize forecast accuracy.  
- Evaluated model performance with **residual diagnostics and AIC/BIC selection**.  

### **2️⃣ SARIMA: Forecasting Madrid’s Average Temperature**  
📌 **Dataset:** [Madrid Daily Weather](https://www.kaggle.com/datasets/mahdiehhajian/madrid-daily-weather)  
🌡 **Objective:** Predict Madrid’s average temperature using a seasonal time series model.  
🔧 **Approach:**  
- Applied **SARIMA (Seasonal ARIMA)** to model seasonal temperature variations.  
- Conducted **seasonality analysis** and applied differencing to remove trends.  
- Optimized seasonal parameters **(P, D, Q, s)** using model selection criteria.  
- Included **confidence intervals** in the forecast to assess uncertainty.  
- Used **SARIMAX** to explore potential external regressors (if applicable).



### ** 3 SARIMAX:  Forecasting Instambul's Traffic 

This repository contains a time series analysis project focusing on daily traffic patterns in Istanbul. The study employs the **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors)** model, incorporating **public holidays as exogenous variables** to improve forecasting accuracy.  Source: https://www.kaggle.com/datasets/leonardo00/istanbul-traffic-index

## 📌 Key Features:  
- **Traffic Profile Analysis:** Examines daily traffic trends in Istanbul.  
- **SARIMAX Model Implementation:** Uses seasonal ARIMA with external regressors (holidays) for enhanced prediction.  
- **Exogenous Variables:** Public holidays are considered as external factors affecting traffic patterns.  
- **Data Preprocessing & Visualization:** Includes data cleaning, feature engineering, and exploratory data analysis.  
- **Forecasting & Model Evaluation:** Compares predictions with actual traffic data to assess model performance.  

This project provides valuable insights into how external factors like holidays influence urban traffic, offering a **data-driven approach to transportation planning and decision-making.**  


## **Tools & Libraries**  
✔ **Python**  
✔ **Statsmodels** (for time series modeling)  
✔ **Matplotlib & Seaborn** (for visualization)  
✔ **Pandas & NumPy** (for data manipulation)  
✔ **Plotly** (for interactive visualizations)  

## **Results & Insights**  
- ARIMA successfully modeled global population growth with minimal differencing.  
- SARIMAX effectively captured seasonal temperature variations in Madrid.  
- Both models highlight the importance of **stationarity, seasonal components, and hyperparameter tuning** in time series forecasting.  




---  
