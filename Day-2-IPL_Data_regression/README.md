
# 🏏 IPL Score Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **total runs scored in an IPL match innings** using Machine Learning techniques.
The goal is to analyze historical IPL data and build a model that can estimate match scores based on team, venue, and contextual features.

---

## 🎯 Problem Statement

Predict the **total runs (****`total_runs`****)** scored in an innings using match-related features such as:

* Batting team
* Venue
* City
* Toss decision
* Historical performance trends

---

## 📂 Dataset

The dataset contains IPL match data from **2008 to 2024**, including:

* Match details (venue, city, date)
* Team information
* Toss details
* Match outcomes
* Performance statistics

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Handled missing values
* Removed irrelevant columns (e.g., match_id, date)
* Checked data consistency

---

### 2️⃣ Feature Engineering (Key Part 🔥)

Created meaningful features to improve model performance:

* `team_avg_score` → Average score of batting team
* `venue_avg_score` → Average score at venue
* `team_venue_avg` → Team performance at specific venue
* `city_avg_score` → Average score in city
* `season_avg_score` → Seasonal trend
* `toss_win` → Whether batting team won toss

---

### 3️⃣ Encoding

* Applied **One-Hot Encoding** on categorical variables:

  * batting_team
  * venue
  * city
  * toss_decision

---

### 4️⃣ Model Building

Trained multiple models:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

### 5️⃣ Model Evaluation

Evaluation metrics used:

* **MAE (Mean Absolute Error)**
* **R² Score**

---

## 📊 Results

| Model             | MAE | R² Score |
| ----------------- | --- | -------- |
| Linear Regression | ~16 | ~0.56    |
| Random Forest     | ~16 | ~0.56    |
| XGBoost           | ~16 | ~0.56    |

---

## 🔍 Key Insights

* Feature engineering significantly improved model performance
* Aggregated features (team & venue averages) were highly impactful
* Advanced models did not outperform linear regression due to limited feature complexity
* Cricket score prediction is inherently uncertain

---

## ⚠️ Challenges Faced

* Data leakage (initially using post-match features)
* Limited predictive power of match-level data
* Handling missing values in city-based features

---

## 💡 Conclusion

This project demonstrates how **feature engineering plays a crucial role** in machine learning performance.
Even simple models can perform well when meaningful features are used.

---

##
