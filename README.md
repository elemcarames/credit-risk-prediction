# Credit Risk Prediction 💳

Machine learning models to predict credit default risk using real-world financial data.

## 📊 Project Overview

Built and compared three classification models to predict whether a borrower
will experience serious financial distress in the next two years.

**Dataset:** [Give Me Some Credit — Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit)
- 150,000 records | 10 features | 6.68% default rate

## 🔍 Methodology

- Exploratory data analysis and missing value treatment
- Class imbalance handling via oversampling
- Feature scaling with StandardScaler
- Model comparison with ROC-AUC as primary metric

## 🤖 Models & Results

| Model | AUC-ROC |
|---|---|
| **Gradient Boosting** | **0.8689** |
| Random Forest | 0.8376 |
| Logistic Regression | 0.8324 |

> Gradient Boosting achieved the best performance with AUC-ROC of 0.8689,
> which is considered strong for credit risk applications.

## 📈 Key Findings

- `RevolvingUtilizationOfUnsecuredLines` was the most predictive feature
- Past delinquencies (90+ days late) are strong default indicators
- High recall on default class prioritized to minimize undetected risk

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)

## 📁 Structure
