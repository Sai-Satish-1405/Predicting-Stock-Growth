# 📊 Predicting Stock Growth (2015–2025)

A technical analysis of stock trends across nine industries using historical data and ARIMA modeling to forecast growth through 2030.

---

## 🔍 Project Summary

This study evaluates stock performance from 2015 to 2025 and predicts future growth using ARIMA (1,1,1). It identifies high-performing sectors and offers insights for long-term investment strategies.

---

## 🏭 Industries Covered

- Technology  
- Finance  
- Retail  
- Healthcare  
- Automotive  
- Semiconductors  
- E-commerce  
- Entertainment  
- Telecommunications  

---

## ⚙️ Methodology

- **Model Used**: ARIMA (1,1,1)  
- **Forecast Horizon**: 2025–2030  
- **Metrics**: MAE, MSE, RMSE, MAPE  
- **Best Accuracy**: Retail (MAPE: 0.16%)  
- **Lowest Accuracy**: Finance & Entertainment (MAPE > 25%)  

---

## 🧪 Data Pipeline

- **Source**: `Stocks.csv` (25 organizations)  
- **Steps**:
  - Date formatting & feature extraction  
  - Industry mapping  
  - Outlier removal (IQR method)  
  - Winsorization for stability  
  - Feature engineering: Daily Range, Net Change, % Change  

---

## 📈 Forecast Highlights

| Industry        | 2025 Forecast | 2030 Forecast |
|----------------|---------------|----------------|
| Technology      | 186.04        | 233.40         |
| Semiconductors  | 128.50        | 172.58         |
| Retail          | 77.10         | 77.22          |
| Healthcare      | 4.56          | -16.35         |

---

## 👥 Contributors

- **Sai Satish Pallapolu** – Modeling, Analysis, Visualization, Data Collection, EDA. 

---

## 📚 References

- Adebiyi et al. (2014) – ARIMA vs ANN  
- Dhyani et al. (2020) – ARIMA for stock forecasting  
- Ma (2020) – ARIMA, ANN, LSTM comparison  
- Noor Zaman et al. (2023) – ML & sentiment analysis  

---

> 💡 *This project bridges the gap in sector-level forecasting using ARIMA, offering actionable insights for long-term investment strategies.*
