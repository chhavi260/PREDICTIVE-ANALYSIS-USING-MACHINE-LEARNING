# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
💻 CodTech Internship - Task 1: Big Data Analysis
🧑‍🎓 Intern Details
Name: Chhavi Chhonker
Intern ID: CT04DZ1916
Batch Duration: 4 Weeks
Mentor Name: Neela Santhosh Kumar
College: CMR Engineering College
Domain: Data Analysis
# 📊 CodTech Internship - Task 2: Predictive Analysis using Machine Learning

## 🎯 Objective
Build a regression model using machine learning to predict students' math scores based on demographic and academic features.

---

## 📁 Dataset
- **Source:** [StudentsPerformance.csv (GitHub)](https://raw.githubusercontent.com/rashida048/Datasets/refs/heads/master/StudentsPerformance.csv)
- **Records:** 1000 students
- **Features:** Gender, race/ethnicity, parental education, lunch type, test preparation, reading/writing scores

---

## 🧠 Workflow Summary

### 📌 1. Data Preprocessing
- Checked for missing values (✅ none)
- Encoded categorical variables using One-Hot Encoding
- Selected `math score` as the target variable

### 🛠️ 2. Model Training
- **Model Used:** Linear Regression (from Scikit-learn)
- **Train-Test Split:** 80/20

### 📈 3. Model Evaluation
- **Mean Squared Error (MSE):** `29.09`
- **R² Score:** `0.88`

> ✅ The model explains 88% of the variance in math scores – good performance for a basic model.

---

## 🔍 Feature Importance
Used coefficients to identify key predictors of math score:
- Positive impact: `reading score`, `writing score`, `test preparation completed`
- Lower impact: parental education, gender

---

## 🖼️ Screenshots
### 🔹 Feature Selection


### 🔹 Model Training


### 🔹 Evaluation Output

---

## 💻 Tools & Libraries
- Google Colab
- Python
- Pandas
- Scikit-learn
- Matplotlib (optional, for visualizations)

---

## ✅ Deliverables
- [x] Notebook with feature selection, model training, and evaluation
- [x] Clean, commented code
- [x] GitHub repository with screenshots

---


