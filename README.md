# COFORGE Stock Price Forecasting using ARIMA

## Student Details
- Name: Tahiya Ishaque Raza
- Roll No: 46
- Stock: COFORGE
- Subject: Data Analytics and Visualization

---

## Objective
To analyze COFORGE stock daily closing prices for the last 1 year and forecast the next 30 days closing prices using ARIMA model.

---

## Data Preprocessing
- Converted Date column into datetime format.
- Removed missing values.
- Visualized closing price trend.

---

## Stationarity Test (ADF Test)
- Original closing price series was non-stationary (p-value > 0.05).
- After applying first order differencing (d=1), the series became stationary (p-value < 0.05).

---

## ARIMA Model
- ACF and PACF plots were used to identify ARIMA parameters.
- ARIMA model was trained and fitted on closing price series.

---

## Forecasting Results
- Forecast for next 30 days closing prices was generated.
- Forecast graph was plotted along with historical data.

---

## Interpretation
- Last Closing Price: 1153.90
- Average Forecast Price: 1163.52

Since the forecasted average price is higher than the last closing price, COFORGE stock is expected to show an upward trend for the next 30 days.

---

## Files Included
- Dataset/COFORGE_1year.csv
- Dataset/COFORGE_forecast_30days.csv
- Source_Code/COFORGE_ARIMA_Assignment.ipynb
- Output_Screenshots folder contains all output graphs and screenshots.

---

## AI Ethics & Responsible Usage Declaration
This project is created only for academic purposes.
AI tools were used only for guidance and understanding.
All analysis and coding work was executed and verified by me.
No plagiarism or unethical copying was done.# COFORGE_ARIMA_Roll46
ARIMA forecasting of COFORGE stock for DAV Assignment 1
