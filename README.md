# Castor Crop Price Prediction

This repository contains code and resources for predicting the price of castor crops in the Patan district of Gujarat using time series analysis and machine learning models.

---

## Table of Contents

- [Introduction](#introduction)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Model Evaluation Metrics](#model-evaluation-metrics)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)
- [Future Scope](#future-scope)

---

## Introduction

Predicting agricultural commodity prices helps stakeholders make informed decisions. This project forecasts castor crop prices by leveraging models like ARIMA, SARIMA, ARIMAX, SARIMAX, ARCH, GARCH, VAR, VARMAX, Random Forest, and LSTM.

---

## Data Source

- **Source**: [AGMARKNET](https://agmarknet.gov.in)
- **Locations**: Patan and Siddhpur, Gujarat
- **Period**: 2010–2024

---

## Methodology

1. **Data Collection & Preprocessing**:
   - Cleaned data and handled missing values.
   - Conducted stationarity tests and feature engineering.

2. **Model Training**:
   - Statistical Models: ARIMA, SARIMA, ARIMAX, SARIMAX, ARCH, GARCH.
   - Multivariate Models: VAR, VARMAX.
   - Machine Learning: Random Forest.
   - Deep Learning: LSTM.

3. **Evaluation**:
   - Compared models using RMSE, MSE, AIC, and BIC.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Time Series Analysis: `statsmodels`, `pmdarima`
  - Machine Learning: `scikit-learn`
  - Deep Learning: `TensorFlow`/`Keras`
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`

---

## Model Evaluation Metrics

- **Root Mean Squared Error (RMSE)**  
- **Mean Squared Error (MSE)**  
- **Akaike Information Criterion (AIC)**  
- **Bayesian Information Criterion (BIC)**  

---

## Results

- **Top Models**:
  - LSTM: RMSE = 114.13 (1.80%)
  - Random Forest: RMSE = 422.99 (17.62%)
  - SARIMAX: RMSE = 627.94 (26.16%)
- **Insights**:
  - LSTM captures long-term trends and non-linearities effectively.

---

## Conclusion

The project demonstrates that deep learning models like LSTM outperform traditional methods in forecasting castor crop prices. These predictions can aid farmers and policymakers in making better decisions.

