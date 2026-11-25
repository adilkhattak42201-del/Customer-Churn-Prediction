<h1 align="center">📞 Telecom Customer Churn Prediction</h1>
<p align="center"><b>Machine Learning pipeline to predict customer churn and identify retention drivers using Python, Scikit-Learn, and a tuned Random Forest classifier.</b></p>

## 📌 Project Overview
This project uses Machine Learning algorithms to predict whether a telecom customer is likely to leave the service (**Churn**) or continue using it, helping businesses understand customer retention patterns and proactively reduce churn.

## ✨ Dataset Features
* `Gender`, `Senior Citizen`, `Partner`, `Dependents`
* `Tenure`, `Contract`, `Payment Method`
* `Monthly Charges`, `Total Charges`

## 🔄 Project Workflow
1. Data Loading
2. Data Preprocessing
3. Categorical Encoding
4. Feature Selection
5. Train-Test Split
6. Model Training (Logistic Regression, Decision Tree Classifier, Random Forest Classifier)
7. Model Evaluation (Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix)
8. Model Comparison
9. Hyperparameter Tuning
10. Feature Importance Analysis
11. Model Saving and Verification

## 📂 Repository Files
| File | Description |
|---|---|
| [`customer_churn_data.ipynb`](./customer_churn_data.ipynb) | End-to-end ML workflow, EDA, model training, evaluation, and tuning |
| [`customer_churn_data.xlsx`](./customer_churn_data.xlsx) | Telecom customer dataset |
| [`Telecom_Churn_Prediction_Model.pkl`](./Telecom_Churn_Prediction_Model.pkl) | Tuned Random Forest model saved via `joblib` |

## 🛠️ Tech Stack
`Python` · `Jupyter Notebook` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `Joblib`

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
jupyter notebook
