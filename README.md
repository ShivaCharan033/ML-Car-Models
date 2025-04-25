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

![Price Distribution](./eda/Screenshot%202025-04-25%20at%203.42.24%E2%80%AFPM.png)

---

### 🔹 2. Distribution of Car Mileage

![Mileage Distribution](./eda/Screenshot%202025-04-25%20at%203.42.32%E2%80%AFPM.png)

---

### 🔹 3. Correlation Heatmap

![Correlation Heatmap](./eda/Screenshot%202025-04-25%20at%203.42.41%E2%80%AFPM.png)

---

### 🔹 4. Boxplot: Price Outlier Detection

![Boxplot](./eda/Screenshot%202025-04-25%20at%203.42.48%E2%80%AFPM.png)

---

### 🔹 5. Top 20 Car Makes by Average Price

![Car Make vs Price](./eda/Screenshot%202025-04-25%20at%203.42.55%E2%80%AFPM.png)

---

### 🔹 6. Year-wise Average Price Trend

![Yearly Price Trend](./eda/Screenshot%202025-04-25%20at%203.43.02%E2%80%AFPM.png)

---

## 🤖 Machine Learning Models

### 🔸 Model 1: Regression – Predict Car Price

- **Algorithm:** Random Forest Regressor
- **Features:** `year`, `mileage`, `tax`, `mpg`, `engineSize`
- **Business Use Case:** Help dealerships price used cars more competitively
- **Metrics:**

![Regression Metrics](./models/Screenshot%202025-04-25%20at%203.43.09%E2%80%AFPM.png)

---

### 🔸 Feature Importance (Regression)

![Feature Importance](./models/Screenshot%202025-04-25%20at%203.43.17%E2%80%AFPM.png)

---

### 🔸 Model 2: Classification – High-End vs Affordable

- **Algorithm:** XGBoost Classifier
- **Target:** Labelled by median price cutoff
- **Use Case:** Customer segmentation for promotions
- **Evaluation:**

![Classification Report](./models/Screenshot%202025-04-25%20at%203.43.26%E2%80%AFPM.png)

---

### 🔸 SHAP Explainability (XGBoost)

![SHAP Summary](./models/Screenshot%202025-04-25%20at%203.43.40%E2%80%AFPM.png)

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




