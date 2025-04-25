# 🚗 Car Price Prediction and Classification Project

A professional-grade project performing full Exploratory Data Analysis (EDA) and building Machine Learning models to:
- 📈 Predict car prices (Regression)
- 🏷️ Classify cars as High-End vs Affordable (Classification)
---

## 📂 Project Structure

---

## 📊 Exploratory Data Analysis (EDA)

- **Distribution of Prices**

![Price Distribution](eda/price_distribution.png)

- **Distribution of Mileage**

![Mileage Distribution](eda/mileage_distribution.png)

- **Correlation Heatmap**

![Correlation Heatmap](eda/correlation_heatmap.png)

- **Boxplot for Outliers in Price**

![Price Boxplot](eda/price_boxplot.png)

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
