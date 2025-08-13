# 💸 Price It Right

![Streamlit App Banner](assets/banner.png)

**Price It Right** is an interactive, machine learning-powered pricing simulation tool built with **Streamlit**. It predicts optimal product prices based on real-time business factors like:

- 📈 Demand
- 🌦️ Seasonality
- 🏷️ Competitor pricing
- 📦 Inventory levels

💡 Simulate real-world pricing decisions and instantly visualize their impact using built-in **XGBoost** and **Linear Regression** models — all through a beautiful, interactive dashboard.

---

## 🖼️ Demo Screenshots

> Make sure these images are stored in the `assets/` folder.

### 🔧 Dashboard Overview
![Dashboard Screenshot](assets/screenshot1.png)

### 💰 Revenue vs Price Simulation
![Revenue vs Price](assets/screenshot2.png)

### 🌱 Seasonality Impact on Purchases
![Seasonality Impact](assets/screenshot3.png)

### 📊 Conversion Rate Over Time
![Conversion Trend](assets/screenshot4.png)

---

## 🔧 Features

- 📊 **Demand Forecasting**: Predict purchases using ML.
- 💰 **Pricing Scenario Simulator**: Adjust price, competitor price, season, and inventory — see instant predictions.
- 🌦️ **Seasonality Analysis**: Understand how seasons affect conversion and revenue.
- 🤖 **ML Models Included**:
  - Linear Regression (baseline)
  - XGBoost Regressor (advanced)
- 📉 **Custom Visual Analytics**:
  - Revenue vs Price curves
  - Conversion trends
  - Price elasticity distribution
  - Stock velocity patterns
- 🎨 **Modern UI/UX**: Custom CSS for a sleek Streamlit dashboard.

---

## 🚀 Run This Project in Google Colab

### 1️⃣ Install Dependencies
```bash
!pip install streamlit xgboost matplotlib seaborn pyngrok --quiet
