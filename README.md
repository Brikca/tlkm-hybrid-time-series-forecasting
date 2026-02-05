# TLKM Stock Price Forecasting Using Hybrid Auto-ARIMA and LSTM

## Overview

This project focuses on **forecasting the stock price of PT Telekomunikasi Indonesia Tbk (TLKM)** using a **hybrid time series and deep learning approach**. The stock market is a complex and dynamic system influenced by economic, social, and psychological factors, making prediction challenging. This project combines **Auto-ARIMA** for capturing linear and seasonal patterns, and **Long Short-Term Memory (LSTM)** neural networks for modeling non-linear dynamics, optimized using **Particle Swarm Optimization (PSO)** to improve forecasting accuracy.

The project was developed as part of an **academic assignment** and is also intended for **data science portfolio purposes**.

---

## Objectives

* Analyze historical TLKM stock price movements  
* Compare traditional statistical modeling and deep learning approaches  
* Implement a **hybrid Auto-ARIMA + LSTM model**  
* Apply **Particle Swarm Optimization (PSO)** to enhance LSTM performance  
* Evaluate and visualize forecasting results  

---

## Data Description

## Data Description
* **Data Type**: Secondary financial time series data  
* **Asset**: TLKM (PT Telekomunikasi Indonesia Tbk)  
* **Frequency**: Daily stock prices  
* **Variables**: Date, Open, High, Low, Close, Adj Close, Volume  
* **Source**: Dataset Saham TLKM.JK (Kaggle) – https://www.kaggle.com/datasets/irfansaputranst/dataset-saham-tlkm-jk  

---

## Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Visualization of TLKM stock price trends, volatility, and basic statistical properties  

2. **Auto-ARIMA Modeling**  
   - Automatic order selection to model linear and seasonal components  
   - Baseline statistical forecasting model  

3. **LSTM Modeling**  
   - Data normalization and sequence generation  
   - Deep learning-based forecasting for non-linear patterns  

4. **Particle Swarm Optimization (PSO)**  
   - Optimization of LSTM hyperparameters  
   - Improves model convergence and forecasting accuracy  

5. **Hybrid Forecasting Framework**  
   - Integration of Auto-ARIMA and PSO-optimized LSTM results  
   - Comparative performance evaluation against standalone models  

---

## Key Results

* Auto-ARIMA effectively captures linear and seasonal patterns in TLKM stock prices  
* LSTM captures non-linear dynamics and outperforms ARIMA for medium-term forecasting  
* PSO optimization improves LSTM performance and stability  
* Hybrid ARIMA + PSO-LSTM model provides more accurate forecasts than standalone models  
* Forecast results provide meaningful insights for investment decision-making, while acknowledging challenges due to stock price volatility  

---

## Tools & Technologies

* Python (Google Colab)  
* pandas, numpy  
* matplotlib, seaborn  
* statsmodels  
* TensorFlow / Keras  
* pmdarima (Auto-ARIMA)  
* pyswarms (Particle Swarm Optimization)  

---

## Author

**Brikca Kristal Desfingka**
Undergraduate Student – Statistics
Universitas Gadjah Mada

---

## Related Links

* Google Colab Notebook: [https://colab.research.google.com/drive/1aJhgdqU-0MBHnd85KAtlHOiRDJv-oDHu](https://colab.research.google.com/drive/1KG6jIFFA6BbcTJjgylb7L1ltf5VI-StF?usp=sharing)
* GitHub Profile: [https://github.com/Brikca](https://github.com/Brikca)

---

## Notes

This repository is intended for **academic demonstration and portfolio use only**. The forecasting results should not be interpreted as financial or investment advice.
