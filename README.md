# Stock Price Time Series Decomposition Analysis

## Overview

This project presents a time series decomposition analysis of historical stock prices for three leading Indian companies: **ASIANPAINT**, **BRITANNIA**, and **KOTAKBANK**. Using the additive decomposition model, the project separates stock price movements into trend, seasonal, and residual components, providing a deeper understanding of market behavior over the most recent five-year period.

---

## Objectives

- Analyze long-term stock price movements.
- Identify underlying market trends.
- Detect recurring seasonal patterns.
- Examine irregular or residual fluctuations.
- Compare decomposition results across multiple companies.
- Visualize all decomposition components for effective interpretation.

---

## Dataset

The analysis uses historical stock market data for the following companies:

- ASIANPAINT
- BRITANNIA
- KOTAKBANK

Each dataset contains daily trading information, including:

- Date
- Open Price
- High Price
- Low Price
- Closing Price
- Trading Volume

For consistency, only the most recent **five years** of data are included in the analysis.

---

## Methodology

The project follows these steps:

1. Import and preprocess the historical stock price data.
2. Convert the Date column into a datetime format.
3. Sort observations chronologically.
4. Filter the latest five years of records.
5. Resample daily closing prices into monthly average closing prices.
6. Apply additive time series decomposition.
7. Extract the following components:
   - Original Series
   - Trend
   - Seasonal
   - Residual (Cyclic)
8. Generate comparative visualizations for each company.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Statsmodels

---

## Project Structure

```
Stock-Price-Time-Series-Decomposition/
│
├── ASIANPAINT.csv
├── BRITANNIA.csv
├── KOTAKBANK.csv
├── main.py
├── README.md
└── Output/
```

---

## Output

The project generates decomposition visualizations containing:

- Original Monthly Average Closing Price
- Trend Component
- Seasonal Component
- Residual (Cyclic) Component

These visualizations assist in identifying long-term market direction, recurring seasonal effects, and unexplained price fluctuations.

---

## Applications

This project can be used for:

- Financial Data Analysis
- Time Series Analysis
- Exploratory Data Analysis (EDA)
- Data Science Portfolio Projects
- Academic Research
- Machine Learning Data Preprocessing

---

## Future Enhancements

Potential improvements include:

- Stock price forecasting using ARIMA and SARIMA models.
- Deep learning-based forecasting using LSTM networks.
- Interactive dashboards using Streamlit or Plotly.
- Comparative analysis across additional sectors and companies.
- Integration of technical indicators and forecasting metrics.

---

## Author

**Shravan Karthikl**

M.Sc. Data Science Student

---

## License

This project is intended for educational, research, and portfolio purposes.
