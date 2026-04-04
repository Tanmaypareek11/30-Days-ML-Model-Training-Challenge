# 🎬 Day 1 - Random Forest | Netflix Content Classification

## Overview

This project is part of my **Machine Learning Practice Series**.

In this project, I built models to classify Netflix content into **Movie** or **TV Show** and compared different algorithms to find the most balanced model.

---

## Model Performance

Best Accuracy: **75% (Decision Tree)**
Best Balanced Model: **Random Forest**

* Accuracy: **71%**
* Precision (TV Show): **53%**
* Recall (TV Show): **79%**

---

## 📁 Dataset

Netflix Titles Dataset

---

## ⚙️ Steps Performed

* Data Cleaning & Preprocessing
* Handling Missing Values
* Removing Data Leakage (`duration`, `listed_in`)
* Encoding Categorical Variables
* Train-Test Split
* Model Training (Logistic Regression, Decision Tree, Random Forest)
* Hyperparameter Tuning
* Model Evaluation

---

## 📈 Key Insights

* High accuracy can be misleading due to class imbalance
* Data leakage can give unrealistic results
* Class balancing improves minority class performance
* Random Forest provided better balance than other models

---

## Conclusion

The Random Forest model with class balancing provided the most practical results by improving TV Show detection while maintaining reasonable accuracy. This highlights the importance of balancing performance metrics rather than focusing only on accuracy.

---
