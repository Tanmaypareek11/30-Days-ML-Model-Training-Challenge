# 🐧 Penguin Species Classification (ML Project)

## 📌 Overview
This project focuses on predicting the **species of penguins** using machine learning algorithms based on physical characteristics such as culmen length, culmen depth, flipper length, body mass, island, and sex.

---

## 📊 Dataset Features
- `species` → Target variable  
- `island` → Island name  
- `culmen_length_mm`  
- `culmen_depth_mm`  
- `flipper_length_mm`  
- `body_mass_g`  
- `sex`  

---

## ⚙️ Steps Performed
- Data Loading & Exploration  
- Handling Missing Values (Median & Mode Imputation)  
- Encoding Categorical Variables  
- Feature Scaling  
- Train-Test Split  
- Model Training & Evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- Random Forest Classifier  
- Decision Tree Classifier (Tuned using `max_depth`)  

---

## 📈 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 99.03%   |
| Random Forest       | 98.07%   |
| Decision Tree       | 96.15%   |

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 🔍 Key Insights
- Logistic Regression performed best due to clear class separability  
- Random Forest provided stable and high performance  
- Decision Tree improved after hyperparameter tuning (max_depth)  
- Class 1 showed slightly lower performance due to fewer samples  

---

## 🧠 Conclusion
The project demonstrates a complete machine learning pipeline from preprocessing to model evaluation. Among all models, **Logistic Regression achieved the highest accuracy**, while **Decision Tree tuning improved generalization**.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
