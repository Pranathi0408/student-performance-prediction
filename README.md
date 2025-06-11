# student-performance-prediction
ML model to predict student performance using demographic and academic data

# 🎓 Student Performance Prediction using Machine Learning

## 📌 Overview
This project aims to predict whether a student will pass or fail using demographic and academic information, applying supervised machine learning techniques.

## 📂 Dataset
- Source: Student Performance Dataset
- Key features: studytime, failures, absences, G1, G2, etc.
- Target: Final grade (G3), converted into binary `pass/fail`

## ⚙️ Models Used
- ✅ Random Forest Classifier
- Accuracy: ~85%

## 📊 Feature Importance
Top predictive features:
- G2 (second period grade)
- Failures
- Studytime

## 🧪 How to Run
pip install -r requirements.txt
jupyter notebook
