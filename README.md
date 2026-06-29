# Air Quality Analysis

A time series forecasting project to analyze and predict air quality levels using multiple forecasting models.

## Dataset

The project uses the UCI Air Quality dataset containing hourly averaged responses from an array of metal oxide chemical sensors, along with reference measurements for pollutants including CO, NOx, NO2, C6H6, and O3.

## Project Structure

1. Data Cleaning - Handled missing values and parsed timestamps
2. Exploratory Data Analysis - Visualized pollutant distributions, correlations, and seasonal trends using heatmaps and time series plots
3. Stationarity Testing - Applied Augmented Dickey-Fuller test and seasonal decomposition
4. Model Building - Built and compared multiple time series forecasting models
5. Forecasting - Generated 48-hour ahead forecasts for key pollutants
6. Validation - Evaluated predictions against defined air quality threshold criteria

## Models Used

- ARIMA - AutoRegressive Integrated Moving Average
- SARIMA / SARIMAX - Seasonal ARIMA with exogenous variables
- Auto ARIMA - Automated parameter selection using pmdarima
- Facebook Prophet - Trend and seasonality decomposition based forecasting

## Libraries

- Python
- Pandas
- NumPy
- Statsmodels
- pmdarima
- Prophet
- Scikit-learn
- Matplotlib
- Seaborn
