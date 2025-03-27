# Drought Classification Dataset for Machine Learning

This repository contains the cleaned and processed meteorological dataset used in the study titled:

**"Machine Learning-Based Drought Classification Using Meteorological Data: Toward Smarter Environmental Models for Site Exploration"**  


## 📄 Description

The dataset includes approximately 3 million records of historical meteorological data from various locations across the United States. Each record captures 18 features that reflect environmental and soil-related conditions, such as temperature, humidity, wind speed, and precipitation. These were used as input variables to train and test a Random Forest-based classification model for predicting drought severity.

## 🎯 Target Variable

The target is a categorical drought severity level ranging from **0 (no drought)** to **5 (exceptional drought)**. This classification was derived by rounding continuous drought scores to the nearest integer.

## 📁 Contents

- `train_data.csv`: Cleaned training dataset  
- `test_data.csv`: Cleaned testing dataset  
- `feature_description.md`: Explanation of each meteorological feature (see below)  
- `README.md`: This file

## 📊 Features

| Indicator       | Description                                      |
|----------------|--------------------------------------------------|
| WS10M_MIN       | Minimum Wind Speed at 10 Meters (m/s)           |
| QV2M            | Specific Humidity at 2 Meters (g/kg)            |
| T2M_RANGE       | Temperature Range at 2 Meters (°C)              |
| T2M             | Temperature at 2 Meters (°C)                    |
| WS10M           | Wind Speed at 10 Meters (m/s)                   |
| WS50M_MIN       | Minimum Wind Speed at 50 Meters (m/s)           |
| T2M_MAX         | Maximum Temperature at 2 Meters (°C)           |
| WS50M           | Wind Speed at 50 Meters (m/s)                   |
| TS              | Earth Skin Temperature (°C)                    |
| WS50M_RANGE     | Wind Speed Range at 50 Meters (m/s)             |
| WS50M_MAX       | Maximum Wind Speed at 50 Meters (m/s)           |
| WS10M_MAX       | Maximum Wind Speed at 10 Meters (m/s)           |
| WS10M_RANGE     | Wind Speed Range at 10 Meters (m/s)             |
| PS              | Surface Pressure (kPa)                          |
| T2MDEW          | Dew/Frost Point at 2 Meters (°C)               |
| T2M_MIN         | Minimum Temperature at 2 Meters (°C)            |
| T2MWET          | Wet Bulb Temperature at 2 Meters (°C)          |
| PRECTOT         | Precipitation (mm/day)                          |

## 🔍 Source

The original raw meteorological data was obtained from a publicly available Kaggle repository:  
[US Drought & Meteorological Data](https://www.kaggle.com/code/cdminix/starter-us-drought-meteorological-data)

Only the raw data was used from Kaggle; all cleaning, feature engineering, and model development were done independently by the author.



For questions or collaborations, please contact:  
**Sarina Shahhosseini**  
shahhos1@asu.edu  
Ph.D. Student, Arizona State University
