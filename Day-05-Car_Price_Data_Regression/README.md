# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the price of cars based on various features such as engine size, mileage, fuel type, horsepower, and more. Multiple regression models were applied and compared to identify the best-performing model.

---

## 📊 Dataset Features

* Car_ID
* Brand
* Model_Year
* Engine_Size
* Fuel_Type
* Transmission
* Mileage
* Doors
* Owner_Count
* Horsepower
* Price (Target Variable)

---

## ⚙️ Data Preprocessing

* Dropped irrelevant column: `Car_ID`
* Handled categorical variables using **One-Hot Encoding (`pd.get_dummies`)**
* Split dataset into training and testing sets

---

## 🤖 Models Used

* Linear Regression
* XGBoost Regressor (with Hyperparameter Tuning)

---

## 📈 Model Performance

### 🔹 Linear Regression (Best Model)

* R² Score: **0.9645**
* MAE: **1442.39**
* RMSE: **1663.28**

### 🔹 XGBoost Regressor (Tuned)

* R² Score: **0.9526**
* MAE: **1550.92**
* RMSE: **1864.65**

---

## 🧠 Key Insights

* Linear Regression outperformed complex models like XGBoost
* Indicates that the dataset has **strong linear relationships**
* Hyperparameter tuning improved XGBoost performance significantly

---

## 🏆 Final Conclusion

Linear Regression achieved the best performance with the highest R² score and lowest error, making it the most suitable model for this dataset.

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib / Seaborn

---


---
