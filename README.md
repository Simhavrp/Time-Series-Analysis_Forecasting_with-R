This R script conducts time series analysis and forecasting on the "oil.csv" dataset. It includes data preprocessing, imputation of missing values, seasonal decomposition, model selection (ARIMA, SARIMA, ETS, STLF, Holt-Winters), model adequacy checks, and comparison of model accuracy metrics (MAE).

Requirements:

R programming environment
Required R packages: zoo, forecast, ggplot2, tseries

Instructions:

Install the required R packages if not already installed (install.packages(c("zoo", "forecast", "ggplot2", "tseries"))).
Set the working directory to where the "oil.csv" file is located.
Run the script in R or RStudio.

Files:

README.md: This file providing an overview of the script.
time_series_analysis.R: R script containing the time series analysis and forecasting code.
Usage:
Read and understand the structure of the "oil.csv" dataset.
Preprocess the data, handle missing values, and perform seasonal decomposition.
Select appropriate time series models (ARIMA, SARIMA, ETS, STLF, Holt-Winters).
Check the adequacy of the selected models.
Compare model accuracy using Mean Absolute Error (MAE).

References:

zoo

forecast

ggplot2

tseries
