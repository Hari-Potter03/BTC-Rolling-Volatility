# Bitcoin Rolling Volatility Analysis

Explore Bitcoin’s volatility using rolling windows and time series visualizations.

---

## 🚀 Project Goals
- Analyze Bitcoin’s price history
- Create rolling features for returns and volatility
- Visualize trends and risk over time

---

## 📦 Dataset
- Source: [Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)

---

## 📌 Coding Exercises

### 1. Preprocessing
- Parse datetime column and sort chronologically
- Compute daily `log_return` = log(close / previous_close)
- Remove weekends or duplicate dates if needed

### 2. Rolling Features
- Calculate:
  - 7-day rolling mean/volatility of close price
  - 30-day rolling log returns
- Plot rolling volatility over time

### 3. Visualization
- Line plot: closing price vs 7-day and 30-day rolling means
- Plot 7-day vs 30-day volatility
- Overlay log returns and identify high-volatility periods

---

## 🧠 Key Questions
- What periods had the highest volatility?
- How does short-term vs long-term volatility compare?
- Could you use volatility as a trading signal?

---
