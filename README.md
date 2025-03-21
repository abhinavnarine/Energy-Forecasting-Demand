# PROJECT2
# Time Series Forecasting of IT Load and Solar Generation

This project focuses on analyzing and forecasting the IT load and solar power generation data over time using ARIMA (AutoRegressive Integrated Moving Average) models. The dataset includes hourly data for IT load and solar generation, and the goal is to predict future values based on historical trends.

## Project Overview

In this project, we perform the following steps:

1. **Data Loading & Preprocessing**: The raw dataset is loaded, missing values are handled, and the data is prepared for analysis.
2. **Exploratory Data Analysis (EDA)**: We analyze the trends in IT load and solar generation over time.
3. **Stationarity Testing**: The stationarity of the time series data is tested using the Augmented Dickey-Fuller (ADF) test.
4. **Time Series Forecasting**: We apply the ARIMA model to both IT load and solar generation data and evaluate model performance using Root Mean Squared Error (RMSE).
5. **Model Evaluation**: We compare the actual vs predicted values to assess the accuracy of the forecast.

## Data

The dataset used in this project contains the following columns:

- **utc_timestamp**: Timestamp of the data entry (in UTC).
- **IT_load_new**: IT load values (in some unit).
- **IT_solar_generation**: Solar generation values (in some unit).

### Dataset Source

The data is provided in the file `TimeSeries_TotalSolarGen_and_Load_IT_2016.csv`, and is assumed to be available in the project directory.

## Requirements

To run this project, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
