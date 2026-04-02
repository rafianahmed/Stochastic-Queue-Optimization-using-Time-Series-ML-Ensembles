# 🍽️ Optimization Restaurant Queueing System

A data-driven project combining **time-series forecasting, machine learning, and simulation** to analyze restaurant demand and improve queueing efficiency.

---

## 🚀 Overview

Restaurant demand fluctuates due to weekdays, seasonality, and holidays, impacting queues, waiting times, and staff utilization.

This project builds an **end-to-end pipeline** to:
- Forecast demand  
- Analyze patterns  
- Support operational optimization  

---

## 🎯 Key Features

- ARIMA + STL time-series forecasting  
- ML prediction (gradient boosting)  
- Feature engineering (lags, rolling stats, holidays)  
- Spline-based missing value imputation  
- Recursive forecasting  
- Ensemble modeling (stat + ML)  
- Time-based demand simulation  

---

## 📂 Structure

```
├── naive.ipynb
├── improved.ipynb
├── time_simulation.ipynb
├── time_simulation_ver2.ipynb
├── Project Presentation.mp4
└── README.md
```

---

## 🧠 Method

1. Data preprocessing (time features, cleaning)  
2. Missing value imputation (cubic spline)  
3. Time-series modeling (STL + ARIMA)  
4. Feature engineering (lags, rolling avg, holidays)  
5. ML modeling (boosting regression)  
6. Ensemble forecasting  
7. Simulation for queue analysis  

---

## 📊 Applications

- Demand forecasting  
- Queue length estimation  
- Staff optimization  
- Peak-hour detection  
- Restaurant operations strategy  

---

## 🛠️ Tech Stack

Python, pandas, numpy, matplotlib, scipy, statsmodels, scikit-learn, lightgbm, xgboost, pytimekr  

---

## ▶️ Run

```
git clone https://github.com/rafianahmed/Optimization-Restaurant-Queueing-System.git
cd Optimization-Restaurant-Queueing-System
pip install numpy pandas matplotlib scipy statsmodels scikit-learn lightgbm xgboost pytimekr jupyter
jupyter notebook
```

Start with `improved.ipynb`

---

## 👤 Author

**Rafian Ahmed Raad — KAIST**

---

## ⭐ Value

- End-to-end data science pipeline  
- Time-series + ML integration  
- Operations optimization application  
