# Optimization Restaurant Queueing System

A data-driven system for modeling and improving restaurant demand forecasting and queue dynamics using time-series analysis, machine learning, and simulation techniques.

---

## Overview

Restaurant operations are highly sensitive to fluctuations in customer demand driven by temporal patterns such as weekdays, seasonality, and holidays. These fluctuations directly impact queue lengths, waiting times, staffing efficiency, and service quality.

This project develops an end-to-end analytical framework that improves forecasting accuracy and supports operational decision-making through simulation.

---

## Key Improvements (Quantified)

- Reduced Mean Absolute Deviation (MAD):  
  ~167,470 → ~118,962 (~30% improvement)

- Reduced Mean Absolute Percentage Deviation (MAPD):  
  ~19.3% → ~14.4%

- Simulation Improvements:
  - Throughput increased: 414 → 425 customers  
  - System inefficiency reduced: ~933.68 → ~891.18 (~4.5% improvement)  
  - System balance improved: ~0.0527 → ~0.0495  

---

## Methodology

1. Data preprocessing and cleaning  
2. Missing value handling using cubic spline interpolation  
3. Time-series modeling (STL decomposition + ARIMA)  
4. Feature engineering (lags, rolling averages, weekday encoding)  
5. Machine learning modeling (gradient boosting)  
6. Ensemble forecasting  
7. Simulation for queue and demand analysis  

---

## Applications

- Demand forecasting  
- Queue optimization  
- Staffing decisions  
- Peak demand detection  

---

## Tech Stack

Python, pandas, numpy, matplotlib, scipy, statsmodels, scikit-learn, lightgbm, xgboost  

---

## Repository Structure

```
├── naive.ipynb
├── improved.ipynb
├── time_simulation.ipynb
├── time_simulation_ver2.ipynb
└── README.md
```

---

## Run

```
git clone https://github.com/rafianahmed/Optimization-Restaurant-Queueing-System.git
cd Optimization-Restaurant-Queueing-System
pip install numpy pandas matplotlib scipy statsmodels scikit-learn lightgbm xgboost jupyter
jupyter notebook
```

Start with `improved.ipynb`

---

## Author

Rafian Ahmed Raad  
KAIST — Computer Science & Business Technology Management  

---

## Value

- Improved forecasting accuracy  
- Integrated time-series, ML, and simulation  
- Applied operations research for real-world optimization  
