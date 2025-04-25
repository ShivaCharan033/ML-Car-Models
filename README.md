# 🚗 Car Price Prediction & Classification (ML Project)

A professional-grade ML pipeline for predicting used car prices and segmenting vehicles as high-end or affordable — complete with EDA, modeling, explainability, and deployment ideas.

---

## 📂 Project Structure

```
├── eda/                # Exploratory Data Analysis plots
├── models/             # Machine Learning models
├── deployment/         # API / Dashboard Deployment ideas
├── README.md           # Project Overview
├── requirements.txt    # Required Python packages
```
---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 1. Distribution of Car Prices

![Price Distribution](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/1.jpeg?raw=true)

---

### 🔹 2. Distribution of Car Mileage

![Mileage Distribution](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/2.jpeg?raw=true)

---

### 🔹 3. Correlation Heatmap

![Correlation Heatmap](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/3.jpeg?raw=true
)

---

### 🔹 4. Boxplot: Price Outlier Detection

![Boxplot](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/4.jpeg?raw=true
)

---

### 🔹 5. Top 20 Car Makes by Average Price

![Car Make vs Price](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/5.jpeg?raw=true)

---

### 🔹 6. Year-wise Average Price Trend

![Yearly Price Trend](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/7.jpeg?raw=true)

---

## 🤖 Machine Learning Models

### 🔸 Model 1: Regression – Predict Car Price

- **Algorithm:** Random Forest Regressor
- **Features:** `year`, `mileage`, `tax`, `mpg`, `engineSize`
- **Business Use Case:** Help dealerships price used cars more competitively
- **Metrics:**

![Regression Metrics](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/8.jpeg?raw=true)

---

### 🔸 Feature Importance (Regression)

![Feature Importance](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/9.jpeg?raw=true)

---

### 🔸 Model 2: Classification – High-End vs Affordable

- **Algorithm:** XGBoost Classifier
- **Target:** Labelled by median price cutoff
- **Use Case:** Customer segmentation for promotions
- **Evaluation:**

![Classification Report](./models/Screenshot%202025-04-25%20at%203.43.26%E2%80%AFPM.png)

---

### 🔸 SHAP Explainability (XGBoost)

![SHAP Summary](https://github.com/ShivaCharan033/ML-Car-Models/blob/main/10.jpeg?raw=true)

---

## 📈 Business Value Summary

| Model        | Purpose                          | Business Value                                | Deployment Option        |
|--------------|----------------------------------|------------------------------------------------|--------------------------|
| Regression   | Predict car resale price         | Optimize pricing for dealerships               | REST API / Dealer CRM    |
| Classification | Segment cars (high-end vs. budget) | Targeted marketing, personalized campaigns | Web dashboard / CRM sync |

---

## 🧰 Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
shap
plotly




