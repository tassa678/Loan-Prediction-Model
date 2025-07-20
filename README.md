# Loan-Prediction-Model
Built a classification model to predict loan approval status using applicant income, credit history, and demographic features.


This project builds a supervised machine learning model to predict whether a loan application will be approved. The dataset includes applicant demographics, income, education, and credit history.

 Overview

- Dataset: Loan Prediction Problem (Kaggle)
- Techniques: Logistic Regression, Label Encoding, Imputation, Classification Metrics
- Tools: Python, pandas, scikit-learn, seaborn

 Key Findings

- Model performed well for approved loans (91% recall), but poorly for unapproved ones (24% recall).
- Strong class imbalance impacted the model's fairness and predictive ability.
- 29 false positives and 8 false negatives highlight a bias toward approval.

 What I Learned

- How to preprocess mixed data types (categorical + numerical)
- Importance of handling class imbalance in binary classification
- Interpreting model performance with confusion matrix and F1-score
