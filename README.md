# 📊 Dual Analysis Project

This project explores two distinct but powerful areas of data analysis: **Time Series Forecasting** using weather data and **Logistic Regression Analysis** using a cardiac health dataset. The goal is to demonstrate practical applications of forecasting and classification models, and to evaluate their effectiveness in real-world scenarios.

---

## 🗓️ Part A: Time Series Analysis – Weather Forecasting

### 📌 Overview
The first part of this project involves a time series analysis of historical weather data from **Met Éireann’s Dublin Airport weather station**. The dataset, in CSV format, contains 9 features and several hundred entries.

The variable of interest is:

> **`maxtp` – Maximum Air Temperature (°C)**

This analysis was selected based on the last digit of my student number.

### 🧪 Methods Used
- **Simple Moving Average (SMA)**
- **Exponential Smoothing**
- **ARIMA**
- **SARIMA**

### 🧠 Key Findings
- **Exponential Smoothing** yielded the most accurate forecast with the lowest:
  - **RMSE**: 3.03
  - **MSE** and **MAE**: Also low compared to other models
- **SARIMA** had higher RMSE (3.495)
- **ARIMA** was not suitable due to seasonal patterns in the data
- Some autocorrelation and non-normality were present in the dataset

---

## ❤️ Part B: Logistic Regression – Cardiac Dataset Analysis

### 📌 Overview
The second part involves a **binary logistic regression analysis** of a cardiac dataset containing **100 participants**, also in CSV format. The aim was to identify key factors influencing the presence or absence of cardiac conditions.

### 🧪 Approach
- Descriptive statistics
- Visualizations
- Dimensionality reduction
- Intermediate and final logistic models

### 🧠 Key Findings
- The **final logistic regression model** showed:
  - **Accuracy**: 0.80
  - **Precision (avg)**: 0.81
  - **Recall (avg)**: 0.80
  - **F1 Score (avg)**: 0.80
  - **AUC**: High (supporting model performance)
- Dimensionality reduction gave **lower accuracy (0.7)** and was not used in final evaluation

---

## 🛠️ Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Statsmodels**, **SciPy**, **scikit-learn**
- **Matplotlib**, **Seaborn**

---

## 📈 Conclusion

This dual-project showcases how:
- **Time series techniques** can be used for **forecasting real-world seasonal data** like temperature.
- **Logistic regression models** are effective in **classifying health conditions** when proper feature selection and evaluation are applied.

---
