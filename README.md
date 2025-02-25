# Time-Series-Forecasting-Tourism-Expenditure-of-Overseas-Visitors-in-Canada

📌 Project Overview
This project applies time series forecasting to analyze and predict overseas visitors' tourism expenditures in Canada using STL, ETS, and ARIMA models. The dataset, sourced from Statistics Canada, includes detailed spending patterns by country of origin and expenditure category (e.g., accommodation, dining, transportation). The results highlight ARIMA as the best-performing model and provide insights to support tourism marketing strategies and infrastructure planning.

🌍 Key Steps:
1. **Data Preprocessing**: Converted quarterly data to monthly time series.
2. **Forecasting Models**:
   - **STL Model**: Fast training, but lower accuracy.
   - **ETS Model**: Adaptable to data changes, but moderate performance.
   - **ARIMA Model**: Best accuracy, but highest computational cost.
3. **Evaluation Metrics**: MSE, MAE, AIC/BIC.

🔍 Key Findings:
- The **ARIMA model** outperformed the others in terms of accuracy.
- Identified **spending patterns by country and category** (e.g., accommodation, dining, transportation).
- Suggested **policy recommendations** for tourism marketing and infrastructure investment.

🔧Technologies Used:
- **R** (`fpp3`, `ggplot2`, `tidyverse`, `forecast`)  
- **Time Series Forecasting & Data Visualization**  

📄 Full Report  
For a detailed analysis, check out the **[Final Report](https://github.com/ChuyueCui/Time-Series-Forecasting-Tourism-Expenditure-of-Overseas-Visitors-in-Canada/blob/main/Reports/Final%20report%20Final%20Version%20.pdf)**.
