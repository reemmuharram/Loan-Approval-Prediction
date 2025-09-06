# Loan Approval Prediction - Binary Classification 💵

🚀 Streamlit Demo: https://loan-approval-prediction-mvjrlxuuaer7tmykne4dar.streamlit.app/

# Content:
```
Loan-Approval-Prediction/
├── model.ipynb
├── app.py
├── requirements.txt
├── model.pkl
.
```
---

# 🧩 Features
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

---
# 🔧 Technologies Used:
- Python 3.x
- Streamlit
- Pandas
- Numpy
- Scikit-learn
- joblib
---
## 📓 Notebook Content:
- `model` – Jupyter Notebook with:
  - Data Exploration  
  - Data Cleaning 
  - Data Visualization (Pie Charts, Histograms, Count Plots, Correlation Matrix Heatmap)
  - Check and Clip Outliers at 1st and 99th Quantiles
  - Data Preprocessing (Encoding, Scaling)
  - Build a training pipeline for a Logistic Regression model, with the original imbalanced data. The pipeline is for scaling and training the model
  - Logistic Regression model evaluation, Classification Report, and Confusion Matrix
  - Build a training pipeline for a Logistic Regression model, and resample the data using SMOTE. The pipeline is for scaling, resampling, and training the model.
  - Logistic Regression model (with resampling) evaluation, Classification Report, and Confusion Matrix
  - Decision Tree model training, Evaluation, Classification Report, and Confusion Matrix
  - A Dataframe to compare the performances of the 3 models, focusing on Precision, Recall and F1 Score
---
## 🚀 Summary
- Logistic Regression provides a solid and interpretable baseline.
- Resampling with SMOTE improves precision.
- Decision Tree achieves the best overall.
---



