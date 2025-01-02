# 🚀 Intelligent Oil Price Prediction Using Advanced Machine Learning Models and Neural Networks

<p align="center">
    <a href="https://github.com/M-RezaeiGH">
        <img src="https://github.com/user-attachments/assets/606f038d-0bc6-4937-8d74-faea00e0b886" alt="Final Project Badge">
    </a>
</p>

<p align="center">
    <a href="https://www.python.org">
        <img src="https://img.shields.io/badge/Python-3.10.7-blue.svg" alt="Python">
    </a>
    <a href="https://www.tensorflow.org">
        <img src="https://img.shields.io/badge/TensorFlow-2.12.0-orange.svg" alt="TensorFlow">
    </a>
    <a href="https://keras.io">
        <img src="https://img.shields.io/badge/Keras-2.12.0-red.svg" alt="Keras">
    </a>
    <a href="https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html">
        <img src="https://img.shields.io/badge/ARIMA-Model-green.svg" alt="ARIMA">
    </a>
    <a href="https://facebook.github.io/prophet/">
        <img src="https://img.shields.io/badge/Prophet-Model-yellow.svg" alt="Prophet">
    </a>
</p>

----
## 👨‍💻 Developer

**Mohammad Reza Rezaei**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://www.linkedin.com/in/m-rezaei/)

---

## 🌟 Purpose and Necessity of the Project

The goal of this project is to predict future oil prices using Advanced Machine Learning Models and Neural Networks. Given the importance of oil prices in the global market and their impact on the economy, accurate oil price predictions can assist companies and investors in making better decisions.

Oil price prediction is a complex challenge due to various influencing factors like global supply, political situations, and economic conditions. By leveraging neural networks, hidden patterns in past data can be identified to make more accurate future predictions.

---

## 📊 Dataset Introduction

The dataset used contains **1,262,329 rows** of real crude oil price data, which includes the following columns:

1. **📅 DATE**: The date corresponding to the oil price at a specific point in time.
2. **⏰ TIME**: The time associated with the oil price at that particular moment.
3. **📈 OPEN**: The opening price of oil at a specific time, representing the price at which the first trade occurs after the market opens.
4. **📊 HIGH**: The highest price at which oil was traded during the specific time period.
5. **📉 LOW**: The lowest price at which oil was traded during the specific time period.
6. **💹 CLOSE**: The closing price of oil, or the price at which the last trade occurred before the market closed for that time frame.
7. **🔄 TICKVOL**: The number of price changes (ticks) within a specified period. Higher TICKVOL means more frequent price changes, indicating higher market volatility.
8. **📦 VOL**: The total number of units (barrels of oil) traded during a specific time frame, representing the market's activity.
9. **⚖️ SPREAD**: The difference between the bid price (buyer) and the ask price (seller), with values of 0 (tight), 1 (medium), and 2 (wide).

---

## 🔧 Project Implementation Methods

1. **📊 Data Visualization**:  
   - Exploratory Data Analysis (EDA) on dataset columns using libraries like `matplotlib`, `seaborn`, `ydata_profiling`, `dtale`, and `klib`.

2. **🧹 Feature Engineering, Data Cleaning, and Splitting**:
   - Preprocessing, anomaly detection (using ADTK), normalization, and data splitting into training and test sets.

3. **📉 ARIMA Model**:
   - Stationarity checks and forecasting using the ARIMA model.

4. **🔮 Prophet Model**:
   - Implementation of Prophet for time-series forecasting using different approaches.

5. **🤖 Neural Networks**:
   - Architecture design using **CNN** and **LSTM** networks for time-series forecasting, with training, evaluation, and error calculation using metrics like Mean Squared Error (MSE).

---

## 🛠️ Installing all libraries with a single command

To install all packages, download the `requirements.txt` file run:

```bash
$ pip install -r requirements.txt
```

---

## 📝 License

This project is licensed under the **Apache Licence 2.0**.

---

## 🗂️ Selected Libraries:

- `numpy==1.23.5`
- `pandas==1.5.3`
- `tensorflow==2.12.0`
- `keras==2.12.0`
- `prophet==1.1.5`
- `seaborn==0.12.2`
- `matplotlib==3.6.3`
- `plotly==5.24.0`
- `statsmodels==0.13.5`
- `ydata_profiling==4.1.2`
- `sweetviz==2.3.1`
- `autoviz==0.1.905`
- `pygwalker==0.4.9.4`
- `pandasgui==0.2.14`
- `dtale==3.13.1`
- `klib==1.1.2`
