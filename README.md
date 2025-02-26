# 🇨🇦 Canada Tourism Expenditure Forecasting

## 📌 Project Overview  
This project analyzes and forecasts **overseas vacationers' tourism expenditure in Canada** using time-series forecasting techniques. The dataset, sourced from **Statistics Canada (Table 24-10-0047-01)**, includes insights into international tourist spending patterns across different categories, such as lodging, dining, transportation, entertainment, and shopping.

### 🎯 Key Objectives  
- **Understand** tourism expenditure trends by international visitors.  
- **Forecast** future spending patterns using advanced time-series models.  
- **Provide insights** for policymakers and businesses in the tourism sector.  

---

## 📊 Methodology  
We implemented **three forecasting models** to analyze and predict tourism expenditure:

### 1️⃣ STL Decomposition Model  
- Decomposes the time series into **trend, seasonal, and residual components**.
- Handles **any type of seasonality** with flexibility.
- **Strengths:** Robust to outliers and interpretable.
- **Limitations:** Less effective for long-term trend predictions.

### 2️⃣ ETS (Error, Trend, Seasonal) Model  
- Uses **exponential smoothing** to model level, trend, and seasonality.
- Can be adapted to **changing patterns** over time.
- **Strengths:** Handles missing data well, easy to interpret.
- **Limitations:** May struggle with highly volatile data.

### 3️⃣ ARIMA (Autoregressive Integrated Moving Average) Model  
- Combines **autoregressive, differencing, and moving average components**.
- Ideal for capturing **complex trends and seasonal effects**.
- **Strengths:** Most accurate model in our analysis.
- **Limitations:** Requires **longer training time** and fine-tuning.

---

## 📈 Results & Insights  
✅ **USA** is the primary source of international tourists, followed by **China, Japan, and the UK**.  
✅ **Lodging, dining, and transportation** are the largest spending categories.  
✅ **ARIMA outperformed STL and ETS** in forecasting accuracy.  
✅ **ETS provided a balance** between speed and accuracy.  
✅ **STL was the fastest to train** but had the lowest predictive accuracy.  

---

## 🚀 Future Work  
- Incorporate **economic indicators**, exchange rates, and seasonality adjustments.  
- Experiment with **machine learning-based models** (e.g., Facebook Prophet, LSTMs).  
- Develop an **interactive dashboard** for real-time expenditure monitoring.  

---

## 🛠️ Tech Stack  
- **Programming Language:** R  
- **Libraries:** `fpp3`, `tidyverse`, `ggplot2`  
- **Modeling Techniques:** STL Decomposition, ETS, ARIMA  
- **Data Source:** [Statistics Canada (Table 24-10-0047-01)](https://www150.statcan.gc.ca/n1/en/catalogue/24-10-0047-01)  

---

## 📄 Full Report  
For a detailed analysis, check out the **[Final Report](https://github.com/ChuyueCui/Time-Series-Forecasting-Tourism-Expenditure-of-Overseas-Visitors-in-Canada/blob/main/Reports/Final%20report%20Final%20Version%20.pdf)**.
