# NYC EMS Forecasting

This project provides forecasts of weekly emergency medical service (EMS) calls in New York City. It combines historical NYC EMS data with Central Park weather records to generate predictive insights using both **SARIMA** time series models and **Ridge regression**.

## Features

- Fetches NYC EMS daily call counts via the NYC Open Data API.
- Aggregates daily data into weekly counts.
- Fetches NOAA Central Park weather data (temperature, precipitation, snow).
- Creates features such as lagged calls, rolling averages, and temperature anomalies.
- Performs SARIMA modeling with metrics (MAE, RMSE) and future forecasts.
- Trains Ridge regression for comparison with SARIMA.
- Visualizes historical vs. predicted calls and confidence intervals.
- Supports borough-level analysis and zoomed-in period analysis.
- Provides staffing insights based on forecasted high-demand weeks.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/nyc_ems_forecast.git
