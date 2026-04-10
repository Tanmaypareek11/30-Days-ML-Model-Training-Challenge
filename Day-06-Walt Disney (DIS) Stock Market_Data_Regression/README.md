# 📈 Stock Price Prediction using Machine Learning (Disney - DIS)

## 📌 Overview
This project focuses on predicting the **next day closing price** of Disney stock using machine learning models.  
The dataset contains historical stock data including Open, High, Low, Close, and Volume.

---

## 📊 Dataset
- Columns: Date, Open, High, Low, Close, Volume  
- Target: **Next Day Close Price**
- Dataset: Walt Disney (DIS) Stock Market Data

---

## ⚙️ Approach

### 1. Data Preprocessing
- Converted Date column to datetime
- Sorted data based on time
- Handled missing values using `dropna()`

---

### 2. Feature Engineering
- Created lag features:
  - `Close_lag1`
  - `Close_lag2`
- Created target variable:
  - `Target = Close.shift(-1)` (Next day prediction)

---

### 3. Train-Test Split
- Used **time-based splitting (80% train, 20% test)**
- Avoided random shuffling to prevent data leakage

---

### 4. Models Used
- Linear Regression
- Random Forest Regressor

---

## 📈 Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📊 Results

| Model                  | MAE   | MSE    | RMSE  | R² Score |
|-----------------------|------|--------|-------|----------|
| Linear Regression     | 2.18 | 9.98   | 3.16  | 0.9897   |
| Random Forest         | 7.16 | 174.74 | 13.21 | 0.8208   |

---

## 🚀 Key Learnings
- Avoided **data leakage** by shifting target variable  
- Time-based splitting is crucial for stock data  
- Feature engineering (lag features) improves performance  
- Random Forest captures non-linear patterns better than Linear Regression  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---


## 💬 Conclusion
This project demonstrates a realistic approach to stock price prediction using machine learning, focusing on proper data handling, feature engineering, and avoiding common pitfalls like data leakage.

---
