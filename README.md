# 🚗 Car Price Prediction and Classification Project

A professional-grade project performing full Exploratory Data Analysis (EDA) and building Machine Learning models to:
- 📈 Predict car prices (Regression)
- 🏷️ Classify cars as High-End vs Affordable (Classification)
---

## 📂 Project Structure

---

## 📊 Exploratory Data Analysis (EDA)

- **Distribution of Prices**



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

## 🚀 Run Locally

```bash
# 1. Clone
git clone https://

- **Average Price by Car Make**

![Make Average Price](eda/make_price_bar.png)

- **Yearly Price Trend**

![Yearly Price Trend](eda/yearly_trend.png)

---

## 🤖 Machine Learning Models

### 1. Car Price Prediction (Regression)

- **Problem**: Predict the resale price of a car based on features.
- **Algorithm**: Random Forest Regressor
- **Features Used**: `year`, `mileage`, `tax`, `mpg`, `engineSize`
- **Performance**:
  - **MAE**: ~1200
  - **RMSE**: ~2000
  - **R² Score**: 0.88

- **Feature Importance**:

![Feature Importance](models/feature_importance_regression.png)

---

### 2. High-End Car Classification (Classification)

- **Problem**: Classify cars into High-End vs Affordable based on price.
- **Algorithm**: XGBoost Classifier
- **Performance**:
  - **Accuracy**: 89%
  - **ROC-AUC Score**: 0.91

- **SHAP Explainability**:

![SHAP Summary Plot](models/shap_summary_classification.png)

---

## 📈 Business Use Cases

| Model | Use Case | Business Value | Deployment Idea |
|:---|:---|:---|:---|
| Price Prediction | Set optimal car pricing | Maximize resale profits | Deploy as API for car dealerships |
| Customer Segmentation | Identify high-end buyers | Targeted marketing campaigns | CRM integration |

---

## 🚀 Deployment Ideas

- 🛠 **Flask API**: Serve the regression/classification models via REST API.
- 📊 **PowerBI Dashboard**: Display real-time price prediction and car segmentation.
- ☁️ **Cloud Hosting**: Deploy models to AWS Lambda, Azure Functions or GCP Cloud Run.

---

## 🛠 Instructions to Run

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
