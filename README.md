# Sales Forecasting

Sales forecasting using multiple models: Seasonal Naïve, Holt-Winters, ARIMA, SARIMA, and Linear Regression.

---

## Project Objective
The goal of this project is to apply quantitative forecasting techniques (time series + causal models) to predict sales for products in the dataset.

---

## Key Steps
- Performed time series analysis to understand seasonality, trend, and patterns
- Split data into train and test datasets
- Built multiple forecasting models on training data
- Selected the best model based on evaluation results
- Generated forecasts on test data using the final selected model

---

## Models Implemented
- Seasonal Naïve Model  
- Holt-Winters Model (Triple Exponential Smoothing)  
- ARIMA Model  
- SARIMA Model  
- Linear Regression Model  

---

## Conclusion
Multiple time series models and a regression model were evaluated.  
From the results, the **Linear Regression model outperformed the time-series models**.

This makes sense because the dataset showed:
- strong seasonality  
- a clear linear trend  

Regression models assume historical patterns repeat in the future, which matched this dataset well.

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Statsmodels  
- Matplotlib  

---

## Repository Structure
- `sales_forecasting.ipynb` – Main notebook
- `README.md` – Project documentation

[README.md](https://github.com/user-attachments/files/20532150/README.md)
