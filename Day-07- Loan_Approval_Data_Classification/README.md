# 📊 Credit Wise - Loan Approval Prediction

## 🚀 Project Overview
This project focuses on predicting whether a loan application will be approved or not using Machine Learning techniques. It involves data preprocessing, feature engineering, visualization, and model building.

---

## 📂 Dataset
- Dataset: **Loan Approval Dataset**
- Contains applicant details such as income, credit score, employment status, etc.
- Target Variable: **Loan_Approved (Yes/No)**

---

## 🔧 Technologies Used
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing
- Handled missing values using:
  - Mean (numerical features)
  - Most frequent (categorical features)
- Removed unnecessary columns (e.g., `Applicant_ID`)

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Class distribution using pie charts  
- Income and credit score analysis  
- Outlier detection using boxplots  
- Correlation heatmap  

---

### 3️⃣ Feature Engineering
- Label Encoding for:
  - Education_Level  
  - Loan_Approved  
- One-Hot Encoding for categorical features  
- Created new features:
  - `DTI_Ratio_sq`  
  - `Credit_Score_sq`  

---

### 4️⃣ Data Splitting & Scaling
- Train-Test Split (80-20)  
- Feature Scaling using **StandardScaler**

---

## 🤖 Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

---

## 📊 Model Performance

| Model                  | Accuracy | Precision | Recall | F1 Score |
|-----------------------|----------|----------|--------|----------|
| Logistic Regression   | 0.85     | 0.84     | 0.83   | 0.83     |
| K-Nearest Neighbors   | 0.82     | 0.81     | 0.80   | 0.80     |
| Naive Bayes           | 0.78     | 0.77     | 0.76   | 0.76     |

### 🏆 Best Model
**Logistic Regression** performed the best among all models with the highest accuracy and balanced performance across all metrics.

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🔥 Key Insights
- Credit Score and Income play a major role in loan approval  
- Feature engineering improved model performance  
- Logistic Regression performed consistently well  


---

## 💡 Conclusion
This project demonstrates a complete ML pipeline from data preprocessing to model evaluation for a real-world financial problem.
