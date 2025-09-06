# Loan Approval Prediction - Binary Classification 💵

## 🚀 Streamlit Demo
[Try it here](https://loan-approval-prediction-mvjrlxuuaer7tmykne4dar.streamlit.app/)

## 📂 Project Structure
```
Loan-Approval-Prediction/
├── model.ipynb
├── app.py
├── requirements.txt
├── model.pkl
```
## 🧩 Features
- Number of Dependents of the Applicant
- Education of the Applicant
- Employment Status of the Applicant
- Annual Income of the Applicant
- Loan Amount
- Loan Term in Years
- Credit Score
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Assets Value
- Loan Status (Target)

## 🔧 Technologies Used
- Python 3.x
- Streamlit
- Pandas
- Numpy
- Scikit-learn
- joblib

## 📓 Notebook Content
- Data Exploration & Cleaning
- Data Visualization (Pie Charts, Histograms, Count Plots, Correlation Heatmap)
- Outlier Handling (1st & 99th Quantiles)
- Data Preprocessing (Encoding, Scaling)
- Logistic Regression pipeline on original imbalanced data
- Logistic Regression pipeline with SMOTE resampling
- Decision Tree model training and evaluation
- Comparison of all models (Precision, Recall, F1 Score)

## 🚀 Summary
- Logistic Regression provides a solid, interpretable baseline
- SMOTE resampling improves precision
- Decision Tree achieves the best overall
