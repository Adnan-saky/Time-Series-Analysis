# Time Series Analysis with Python

This repository contains Python code for performing Time Series Analysis on a dataset using libraries such as `pandas`, `matplotlib`, and `statsmodels`.

## Dataset

The analysis is performed on a dataset stored in a CSV file named `DataSet.csv`. The dataset contains time series data with the "DATE" column serving as the index, and the "Price" column representing the numerical values.

## Stationarity Check

The code checks the stationarity of the time series data using the Augmented Dickey-Fuller test. It determines if the data is stationary or non-stationary based on the p-value.

## Seasonality Check

The code checks for seasonality in the time series data by plotting the data and adding vertical lines at yearly intervals.

## Autocorrelation

The code calculates the autocorrelation of the "Price" column at various lags (1, 2, 3, 6, and 12 months).

## Decomposition

The code uses the `seasonal_decompose()` function from `statsmodels` library to decompose the time series data into its constituent components - trend, seasonality, and residuals. It then plots the decomposed components.

## License

This code is licensed under the [MIT License](LICENSE).

---
Note: This README file provides an overview of the Time Series Analysis code available in this repository. For detailed implementation, please refer to the source code files.
