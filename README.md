# 📈 Yes Bank Stock Closing Price Prediction

This project aims to predict the **monthly closing stock price** of Yes Bank using machine learning. Explored and analyzed real-world historical stock data and built regression models to forecast future trends, providing meaningful insights for investors and businesses.

---

## 📊 Dataset Overview

- The dataset contains monthly stock prices from **2005 to 2020**.
- Fields include:
  - `Date`
  - `Open`
  - `High`
  - `Low`
  - `Close`
- Year and Month were extracted from the `Date` column for better analysis.

---

## 🎯 Problem Statement

Predict the **monthly closing price** of Yes Bank stock using historical stock features and identify patterns, risks, and opportunities that impact price movement.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scipy
- Scikit-learn
- Pickle

---

## 🔍 Key Steps

### 1. **Data Wrangling & Exploration**

- Converted and sorted dates.
- Extracted `Year` and `Month` from `Date`.
- Checked for missing values, outliers, and feature types.

### 2. **Data Visualization**

- Line plots, bar charts, scatter plots, and heatmaps to understand:
  - Stock performance over time.
  - Correlation between features.
  - Rise and fall patterns.

### 3. **Feature Engineering**

- Selected features: `Year`, `Month`, `Open`, `High`, `Low`.
- Removed highly correlated redundant features to avoid overfitting.

### 4. **Scaling & Splitting**

- Scaled features using `StandardScaler`.
- 80-20 Train-Test split due to small dataset size.

### 5. **ML Model Building**

Models used:

- Support Vector Regressor (SVR)
- Random Forest Regressor (Best)
- Gradient Boosting Regressor

### 6. **Evaluation Metrics**

- `Root Mean Squared Error (RMSE)`
- `R² Score`  
  → **Random Forest achieved R² Score: 0.985**

### 7. **Model Deployment**

- Final model and scaler saved using `pickle`.
- Tested with real-like unseen inputs to ensure reliable predictions.

---

## ✅ Results

- The Random Forest model performed the best with **high accuracy**.
- Realistic predictions for past data validate its reliability.
- The model is ready for deployment or further improvement using time-series approaches.

---

## 💡 Conclusion

This project proves that even with basic regression techniques, it is possible to create reliable **stock price prediction models**. It highlights **machine learning's role** in financial forecasting and decision-making.

---

## 📁 Files Included

- `yes_bank_stock_prediction.ipynb` – Jupyter Notebook with full code
- `model.pkl` – Saved model and scaler
- `README.md` – Project documentation
- `requirements.txt` – Project Dependencies
