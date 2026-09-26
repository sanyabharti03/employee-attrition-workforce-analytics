# Employee Attrition & Workforce Analytics

A machine learning project that analyzes employee attrition patterns and predicts employee attrition risk using HR data.

## Features

- Exploratory Data Analysis of employee attrition
- Attrition analysis by job role, age, income, satisfaction, and tenure
- Logistic Regression and Random Forest models
- Model evaluation using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
- Feature importance analysis
- Employee attrition risk scoring
- Low, Medium, and High risk classification
- What-if analysis for hypothetical employee changes
- Model saving and loading using Joblib

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Dataset

IBM HR Analytics Employee Attrition & Performance dataset.

The target variable is `Attrition`, where:
- `0` = No Attrition
- `1` = Attrition

## Risk Scoring

| Probability | Risk Level |
|---|---|
| < 30% | Low |
| 30% - < 60% | Medium |
| ≥ 60% | High |

## Project Workflow

Data Loading → Preprocessing → EDA → Model Training → Evaluation → Feature Importance → Risk Scoring → What-If Analysis

## Project Structure

```text
employee-attrition-workforce-analytics/
├── Employee_Attrition_Analysis.ipynb
├── README.md
└── requirements.txt
