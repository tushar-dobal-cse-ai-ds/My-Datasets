# 🌍 India City Air Quality Index Dataset (2015–2023)

![AQI Banner](./assets/aqi_banner.png)

## 📌 Overview

This repository hosts the **India City Air Quality Index (AQI) dataset** — a daily record of air pollution levels across major Indian cities from 2015 to 2023.

It is designed for environmental analytics, machine learning, and data storytelling.

---

## 🔗 Kaggle Dataset

This dataset is also published on Kaggle and can be explored/downloaded directly here:

👉 https://www.kaggle.com/datasets/tushardobal/india-city-air-quality-index-dataset-20152023

If you want to run notebooks directly on Kaggle without downloading locally, that’s the best place to start!

---

## 📊 What’s Inside

| Feature | Description |
|---------|-------------|
| `city` | City name |
| `date` | Observation date |
| `pm25` | PM2.5 concentration (μg/m³) |
| `pm10` | PM10 concentration (μg/m³) |
| `no2` | Nitrogen dioxide (NO₂) |
| `so2` | Sulfur dioxide (SO₂) |
| `co` | Carbon monoxide (CO) |
| `o3` | Ozone (O₃) |
| `aqi` | Computed Air Quality Index |
| `aqi_category` | AQI category label |

---

## 📈 Dataset Summary

- 🔹 **Time span:** 2015–2023  
- 🔹 **Frequency:** Daily  
- 🔹 **City count:** 10 major Indian cities  
- 🔹 **Total records:** ~32.8K  
- 🔹 **Use case:** Air pollution analysis & ML modeling

---

## 🚀 Ready for Machine Learning

This dataset is suited for:

- **Regression:** Predict AQI values
- **Classification:** Predict AQI category
- **Time Series:** Forecast future air quality
- **EDA:** Correlation & trend analysis

---

## 🧪 Example ML Workflow

1. Load the dataset  
2. Clean & preprocess
3. Feature engineering (e.g., decomposing `date`)
4. Regression models (Random Forest / XGBoost)
5. Evaluation (R², RMSE, MAE)
6. Visualize feature importance

---

## 🔍 Visualization Ideas

- AQI trend over years
- City-wise pollution comparison
- Heatmap of pollutant correlations
- Dense vs poor AQI days by season

---

## 📁 Repository Structure

