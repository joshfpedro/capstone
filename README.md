# Renewable Energy Production Forecasting

## Project Overview

### Problem Area
This project addresses the challenge of accurately forecasting renewable energy production, specifically focusing on solar and wind energy. The key issues include:
- Predicting energy production levels based on weather conditions
- Understanding the variability and intermittency of renewable energy sources
- Improving grid management and energy distribution planning

### Affected Stakeholders
- Energy providers and utility companies
- Grid operators
- Policymakers and regulators
- Consumers of renewable energy

### Proposed Data Science Solution
We aim to develop and compare various forecasting models to predict renewable energy production:
1. SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors)
2. Random Forest
3. Neural Network
4. Long Short-Term Memory (LSTM) network

These models will:
- Predict solar and wind energy production based on historical data and weather conditions
- Compare the performance of different modeling techniques
- Provide insights into the factors influencing renewable energy production

### Impact
The potential impact of this project includes:
- Improved grid stability and management through accurate energy production forecasts
- Enhanced integration of renewable energy sources into the power grid
- Better decision-making tools for energy providers and grid operators
- Support for policymakers in setting realistic renewable energy targets

### Dataset Description
Our analysis utilizes a dataset containing renewable energy production data and weather information for New York state from 2021 to 2023. The dataset includes:
1. Monthly solar and wind energy production
2. Weather data (temperature, wind speed, precipitation)

#### Data Dictionary
| Variable | Description | Type |
|----------|-------------|------|
| date | Date of observation | Date |
| SUN | Solar energy production | Float |
| WND | Wind energy production | Float |
| temp | Average temperature | Float |
| wind_speed | Average wind speed | Float |
| precipitation | Total precipitation | Float |

This dataset allows for a comprehensive analysis of the factors influencing renewable energy production, enabling the development and comparison of various forecasting models.

## Methodology
1. Data preprocessing and feature engineering
2. Implementation of SARIMAX, Random Forest, Neural Network, and LSTM models
3. Model evaluation using Mean Absolute Error (MAE)
4. Visualization of model performance and forecasts

## Results
The project generates visualizations comparing the performance of different models:
- Bar charts showing MAE for each model and energy type
- Heatmap visualizing MAE across models and energy types
- Time series plots of actual vs. predicted energy production for each model

Results and visualizations can be found in the `docs/figures` directory.

## Future Work
- Incorporate additional weather variables and geographical factors
- Explore ensemble methods combining multiple models
- Extend the analysis to other regions or countries
- Investigate the impact of long-term climate trends on renewable energy production
