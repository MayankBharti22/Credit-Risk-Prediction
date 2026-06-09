# Credit Risk Prediction using Machine Learning

## Overview

This project develops a machine learning pipeline to predict whether a borrower is likely to default on a loan based on demographic, financial, and credit history information.

The objective is to assist financial institutions in identifying high-risk borrowers and improving loan approval decisions.

---

## Dataset

The dataset contains borrower information such as:

* Age
* Income
* Employment Length
* Home Ownership Status
* Loan Purpose
* Loan Grade
* Interest Rate
* Credit History Length
* Previous Default History

**Target Variable:**

* 0 → Non-Default
* 1 → Default

---

## Project Workflow

1. Data Cleaning and Preprocessing
2. Missing Value Treatment
3. Outlier Analysis
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Scaling
7. Model Training
8. Hyperparameter Tuning
9. Model Evaluation

---

## Models Evaluated

| Model                  | F1 Score   |
| ---------------------- | ---------- |
| Decision Tree          | 0.7245     |
| Support Vector Machine | 0.7288     |
| Random Forest          | 0.6902     |
| Tuned Random Forest    | 0.7892     |
| XGBoost                | 0.7977     |
| Tuned XGBoost          | **0.8122** |

---

## Why F1-Score?

The dataset is imbalanced, with significantly fewer default cases than non-default cases.

F1-score was selected as the primary evaluation metric because it provides a balance between Precision and Recall, making it more reliable than accuracy for credit risk prediction.

---

## Final Model

### Tuned XGBoost

**Best Hyperparameters**

```python
{
    "n_estimators": 200,
    "max_depth": 7,
    "learning_rate": 0.2,
    "subsample": 1.0,
    "colsample_bytree": 0.8
}
```

**Final F1 Score**

```text
0.8122
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* StatsModels

---

## Repository Structure

```text
Credit-Risk-Prediction/
│
├── notebooks/
│   └── EDA_of_Credit_Risk.ipynb
│
├── data/
│   └── credit_risk_dataset.csv
│
├── report/
│   └── Credit_Risk_Report.pdf
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

## Results

The tuned XGBoost model achieved the highest F1-score of **0.8122**, outperforming all other evaluated models and demonstrating strong capability in identifying high-risk borrowers.

---

## Author

**Mayank Bharti**
M.Sc. Statistics
Indian Institute of Technology Kanpur
