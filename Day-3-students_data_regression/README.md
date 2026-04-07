# 📊 Student Exam Performance Prediction

## 🚀 Project Overview

This project focuses on analyzing and predicting **student exam performance** using various **regression models**. The goal is to understand how different factors like study habits, attendance, and socio-economic background impact the **Pass or Fail**.

---

## 📁 Dataset Description

The dataset contains multiple features related to students and the dataset is :
Student_exam_performance_dataset.csv


---

## ⚙️ Data Preprocessing Steps

* Removed unnecessary columns (like `student_id`)
* Handled missing values
* Separated features and target:

  * `X` → Input features
  * `y` → `final_exam_score`
* Applied:

  * **Label Encoding** (for target if needed)
  * **One-Hot Encoding** using `pd.get_dummies()` for categorical features
* Feature scaling (if required)

---

## 📈 Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression

---

## 📊 Model Performance

### 🔹 Linear Regression

* R² Score: **0.63**
* MAE: **0.265**
* MSE: **0.0919**
* RMSE: **0.303**

---

### 🔹 Ridge Regression

* R² Score: **0.6304**
* MAE: **0.2651**
* MSE: **0.0919**
* RMSE: **0.3032**

---

### 🔹 Lasso Regression

* R² Score: **0.6297**
* MAE: **0.2666**
* MSE: **0.0921**
* RMSE: **0.3035**

---

## 📌 Insights

* All models show **similar performance (~63% accuracy in variance explained)**
* Ridge Regression performs slightly better than others
* The dataset shows **moderate linear relationships**
* There is scope for improvement using:

  * Feature engineering
  * Non-linear models

---

## 🧠 Conclusion

This project demonstrates how different regression models perform on student data. While Linear, Ridge, and Lasso give **moderate performance**, further improvements can be achieved using advanced techniques.


