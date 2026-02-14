
# 💳 CreditWise – Intelligent Loan Approval System

> AI-Powered Loan Approval Prediction System for SecureTrust Bank

---

## 📌 Overview

CreditWise is a Machine Learning–based intelligent loan approval system developed to help **SecureTrust Bank** automate and optimize its loan verification process.

Traditionally, the bank relied on manual verification of income documents, credit history, and employment details. This process was:

* ⏳ Time-consuming
* ⚖️ Biased and inconsistent
* 📉 Risk-prone

This system leverages historical loan application data to predict whether a loan should be:

* ✅ **Approved (1)**
* ❌ **Rejected (0)**

before final human verification.

---

## 🎯 Problem Statement

SecureTrust Bank faces two major challenges:

1. Worthy customers sometimes get rejected (business loss).
2. High-risk customers sometimes get approved (financial loss).

The goal of this project is to build an **accurate, fast, and unbiased Machine Learning model** that predicts loan approval decisions based on applicant data.

---

## 📊 Dataset Description

Each row represents a loan applicant with personal, financial, and credit attributes.

### 🔹 Features

| Feature            | Description                             |
| ------------------ | --------------------------------------- |
| Applicant_ID       | Unique ID                               |
| Applicant_Income   | Monthly income                          |
| Coapplicant_Income | Co-applicant income                     |
| Employment_Status  | Salaried / Self-Employed / Business     |
| Age                | Applicant age                           |
| Marital_Status     | Married / Single                        |
| Dependents         | Number of dependents                    |
| Credit_Score       | Credit bureau score                     |
| Existing_Loans     | Active loans                            |
| DTI_Ratio          | Debt-to-Income ratio                    |
| Savings            | Savings balance                         |
| Collateral_Value   | Collateral value                        |
| Loan_Amount        | Requested amount                        |
| Loan_Term          | Duration (months)                       |
| Loan_Purpose       | Home / Education / Personal / Business  |
| Property_Area      | Urban / Semi-Urban / Rural              |
| Education_Level    | Graduate / Postgraduate / Undergraduate |
| Gender             | Male / Female                           |
| Employer_Category  | Govt / Private / Self                   |
| **Loan_Approved**  | Target (1 = Approved, 0 = Rejected)     |

---

## 🧠 Machine Learning Pipeline

### 1️⃣ Data Preprocessing

* Handling missing values
* Encoding categorical variables (One-Hot / Label Encoding)
* Feature scaling (StandardScaler)
* Outlier treatment

### 2️⃣ Feature Engineering

* Debt-to-Income insights
* Income-to-Loan ratio
* Credit risk indicators

### 3️⃣ Model Development

Models implemented:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

### 4️⃣ Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

---

## 📈 Business Impact

* 🔍 Reduces loan default risk
* ⚡ Speeds up approval process
* 📊 Improves decision consistency
* 💰 Minimizes financial loss
* 🤝 Supports fair lending practices

---

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy**
* **Scikit-Learn**
* **Matplotlib & Seaborn**
* Jupyter Notebook

---

## 📂 Project Structure

```
CreditWise-Loan-System/
│
├── data/
│   └── loan_dataset.csv
│
├── notebooks/
│   └── loan_model_training.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   └── evaluation.py
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/CreditWise-Loan-System.git
cd CreditWise-Loan-System
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

```bash
jupyter notebook
```

---

## 🔮 Future Improvements

* Deploy as a Web App (Streamlit / Flask)
* Add Explainable AI (SHAP, LIME)
* Real-time prediction API
* Bias & Fairness monitoring
* Integration with banking systems

---

## 👨‍💻 Author

Developed as part of a Machine Learning problem-solving project focused on real-world financial risk management.


