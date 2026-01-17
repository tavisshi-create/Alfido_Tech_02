# Loan Approval Prediction (Supervised Learning)

## 📋 Project Overview
This project builds a machine learning pipeline to automate loan eligibility checks. It addresses real-world data challenges like missing values and class imbalance to provide a fair and accurate prediction model.

## 🛠️ Technical Implementation
* **Data Preprocessing:** Handled missing values in `Credit_History` and `LoanAmount` using statistical imputation.
* **Feature Engineering:** Implemented `StandardScaler` for numerical normalization and `LabelEncoder` for categorical features.
* **Imbalance Handling:** Used **SMOTE** to balance the 'Approved' vs 'Rejected' classes, ensuring the model identifies risky loans effectively.
* **Model Comparison:** Evaluated **Logistic Regression** against **Random Forest** to find the most robust solution.

## 📊 Results & Performance
- **Winning Model:** Random Forest.
- **Metrics:** Reported high Precision, Recall, and ROC-AUC scores.
- **Key Insight:** Credit History was the strongest predictor of loan status.

## 📁 Repository Contents
- `Task2_Loan_Prediction.ipynb`: Complete Python source code.
- `Task2_Report.pdf`: Business-oriented interpretation and deployment strategy.
- `ROC_Curve.png`: Visual comparison of model performance.
