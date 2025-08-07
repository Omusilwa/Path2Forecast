## 📊 Path2Forecast: Excel Time Series Trend and Forecasting Dashboard

**Project Summary**  

This project demonstrates how to uncover patterns and make future predictions using historical data through Excel-based time series analysis. It showcases key forecasting techniques, visual trend diagnostics, and practical use of Excel functions like `FORECAST.ETS`, `FORECAST.LINEAR`, and moving averages.

---

#### 🎯 Objectives:

- To visualize historical data trends using **line plots**
- To apply **Exponential Smoothing Forecasting** (ETS) for time series prediction
- To use Excel’s built-in tools to communicate **confidence intervals** and **seasonality**
- To empower analysts and beginners to perform forecasting without complex coding

---

#### 🧠 Key Concepts Covered:

| Concept                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 📅 Time Series Basics          | Formatting and organizing monthly data for trend analysis                   |
| 📈 Trend Plotting              | Using Excel Line Charts and 7-Day Moving Averages to visualize patterns     |
| 🔮 Forecasting                 | Leveraging `FORECAST.LINEAR` and `FORECAST.ETS` for prediction              |
| 📉 Confidence Intervals       | Understanding upper and lower bounds to quantify prediction accuracy        |
| 🧰 Excel Forecast Sheet Tool   | Automatically generating forecast charts and projections                    |

---

#### 📊 Dashboard Overview

The dashboard titled **Path2Forecast** includes:
1. **Sales Performance Over Time** – A line chart showing historical trends
2. **Weekly Trends** – Bar plot of sales distribution across weekdays
3. **Daily Trends vs 7-Day Average** – Smoothing out fluctuations using a moving average
4. **Projected Trends with Seasonality** – Forecasted sales using ETS with 95% confidence bounds
---

*Dashboard_Design.png*
   <img width="892" height="662" alt="Screenshot 2025-08-06 211621" src="https://github.com/user-attachments/assets/28f73cee-f4b4-4b9e-ae65-1bc72780933a" />


> 🔍 All visuals were created in Excel using formulas, forecast sheets, and custom formatting

---

#### 🧪 Dataset Details

- **File:** `Monthly_Sales_Forecasting_Dataset.xlsx`
- **Period:** January 2022 – December 2022
- **Frequency:** Monthly
- **Variables:**
  - `Date`: End of month
  - `Sales`: Synthetic sales data with embedded trend, seasonality, and noise

---

#### 🔧 Tools & Functions Used

- **Excel Functions:**
  - `=FORECAST.ETS()`
  - `=FORECAST.LINEAR()`
  - `=AVERAGEIFS()`
  - `=TEXT()`, `=MONTH()`, `=YEAR()`, `=DATE()`

- **Excel Features:**
  - Forecast Sheet (under *Data* tab)
  - Line & Bar Chart
  - Trendlines and Confidence Intervals
  - Table formatting and conditional styling

---

#### 🚀 How to Use

1. Open the Excel file: `Monthly_Sales_Forecasting_Dataset.xlsx`
2. Explore the trend manually using charts or generate a **Forecast Sheet**
3. Adjust the forecast period and confidence interval as needed
4. View the `Dashboard_Design.png` for design inspiration





