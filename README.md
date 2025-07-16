# 🧠 Pediatric Appendicitis Prediction (ML Pipeline)

This project develops a robust ensemble-based machine learning pipeline to classify **pediatric appendicitis cases** based on clinical features. It uses Scikit-learn, XGBoost, and data preprocessing techniques to build a reliable and interpretable model suitable for decision support in pediatric care.

---

## 📌 Overview

- Loads pediatric appendicitis data from CSV
- Cleans and preprocesses tabular clinical features
- Trains an ensemble model (Random Forest + XGBoost)
- Evaluates model performance with:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC
- Visualizes feature importance and confusion matrix
- Saves the trained model using `joblib`

---

## 🩺 Features Used

- Age, Gender
- Clinical indicators: nausea, vomiting, abdominal pain, fever, rebound tenderness, and more
- Optional binary and categorical features

---

## 🛠 Requirements

Install dependencies with:

```bash
pip install pandas scikit-learn xgboost matplotlib seaborn joblib
