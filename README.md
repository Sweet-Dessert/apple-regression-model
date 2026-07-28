Apple Revenue Regression

Uses OLS regression to model and forecast Apple's quarterly revenue over time.

Steps
Load qSales_2024.csv, filter to Apple (AAPL).
Plot revenue over time.
Fit a simple trend model: revenue = β0 + β1 * time.
Add a seasonality dummy for fiscal Q1 (holiday quarter) + interaction term, refit model.
Forecast future revenue using synthetic_data.csv.
Files needed
qSales_2024.csv

Requirements
pandas, numpy, statsmodels, matplotlib
