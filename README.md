# Google Stock Price Forecasting using SARIMAX

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-000000?style=for-the-badge)

**Time Series Analysis | SARIMAX Model | Financial Forecasting**

---

### 📋 Project Overview

A robust **time series forecasting** project that predicts Google (GOOGL) stock prices using the **SARIMAX (Seasonal Auto-Regressive Integrated Moving Average with eXogenous regressors)** model. The project demonstrates strong proficiency in statistical modeling, data preprocessing, and financial time series analysis.

**Goal**: Forecast the next 30 days of Google stock closing prices with uncertainty quantification (95% confidence intervals).

---

### ✨ Key Features

- **Real-time data collection** using Yahoo Finance API (`yfinance`)
- **Comprehensive EDA** and stationarity analysis
- **Advanced Time Series Modeling** using SARIMAX with seasonal components
- **Professional visualization** with confidence intervals
- **Production-ready code structure** in Jupyter Notebook

---

### 🛠 Tech Stack

- **Language**: Python 3.13
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Plotly, Matplotlib
- **Time Series Modeling**: Statsmodels (SARIMAX)
- **Data Source**: Yahoo Finance (`yfinance`)

---

### 📊 Model Details

- **Model Used**: SARIMAX(0, 1, 0) × (2, 1, 0, 12)
- **Differencing**: First-order non-seasonal + First-order seasonal differencing
- **Seasonality**: 12 periods (monthly seasonality)
- **Forecast Horizon**: Next 30 days
- **Evaluation**: Visual validation with 95% confidence intervals

---

### 📈 Results Highlights
![Alt text](https://github.com/MishuTI/weather_data_analysis/blob/main/weather.PNG)

- Successfully handled trending financial time series data
- Captured both trend and seasonal patterns
- Generated probabilistic forecasts with confidence bands
- Clean, publication-quality visualizations

*(See notebook for detailed model summary and forecast plots)*


