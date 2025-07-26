# Traffic Volume vs Environmental Factors (Temperature & AQI) Analysis
Simple Linear Regression project predicting air quality from traffic volume

## Project Overview
This project explores how traffic volume correlates with environmental factors, particularly temperature and air quality. Using the **Metro Interstate Traffic Volume** dataset from Kaggle, **Exploratory Data Analysis (EDA)** and **Simple Linear Regression** are applied to identify patterns and dependencies

> 🔍 Goal: Understand how changes in temperature or AQI influence traffic volume using statistical modeling (OLS) and visualization (using seaborna and matplotlib).


## Dataset Information

- **Source:** [Kaggle – Metro Interstate Traffic Volume](https://www.kaggle.com)
- **File Used:** `MetroInterstate_TrafficVolumeDataset.csv`

### KEY FEATURES:
| Column Name        | Description                                           |
|--------------------|-------------------------------------------------------|
| `traffic_volume`   | Number of cars passing on the interstate per hour     |
| `temp`             | Temperature (in Kelvin)                               |
| `weather_main`     | General weather condition (Clear, Rain, Snow, etc.)   |
| `date_time`        | Timestamp of record                                   |

> Other weather-related features include humidity, clouds, wind speed, etc.


## Methods Used
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Heatmaps
- Histplot for Distribution of Traffic Volume
- Model Building (Simple Linear Regression)
- Linear Regression Scatter Plotting
- Performance Metrics: MSE, MAE, RMSE, R²
- Bar Plotting of Performance Metrics
- OLS for Statistical Modelling


## Requirements

To run the notebook, install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

## Use-Case
If temperature or weather data can predict traffic volume reliably, city planners can optimize road maintenance schedules, adjust signal timings, or issue congestion warnings in advance
