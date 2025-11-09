# Monthly Sales Forecasting (Time Series ML)


This project uses historical retail sales data to forecast the next 12 months of sales using a Time Series model (ARIMA).  
The goal is to support better business decision-making through data-driven demand prediction.

---

## Project Steps

1. Load dataset (train.csv)
2. Convert daily data into monthly data
3. Explore seasonal patterns
4. Train ARIMA forecasting model
5. Predict next 12 months sales
6. Visualize actual vs forecasted trend
7. Generate insights for business value

---

## Key Insights

- Sales show strong seasonal patterns repeating every year
- Long-term trend shows sales are gradually increasing
- Forecast suggests future sales remain stable within historical seasonal range
- Businesses can use these predictions for:
  - inventory planning
  - stock purchase decisions
  - budgeting & forecasting
  - marketing timing strategy

---

## Forecasted Next 12 Months (Example)

| Month | Predicted Sales |
|-------|-----------------|
| 2018-01 | ~380,952 |
| 2018-02 | ~385,836 |
| ... | etc |

---

## Files in this Repository

| File | Description |
|------|-------------|
| `train.csv` | original dataset |
| `sales_forecasting.ipynb` | full code + charts |
| `Sales_Forecasting_Project_Explanation.docx` | full written explanation |
| `/images/*` | forecast visuals |
| `README.md` | this document |

---

## Dataset Source

Kaggle — Demand Forecasting Challenge  
https://www.kaggle.com/c/demand-forecasting-kernels-only/data

---

## Tech Stack

Python • Pandas • Matplotlib • Statsmodels (ARIMA) • Jupyter/Colab

---

## Purpose

This project was done to practice Business Analytics and Machine Learning skills by going from:
**Raw data → ML model → Forecast → Business Insights**.
