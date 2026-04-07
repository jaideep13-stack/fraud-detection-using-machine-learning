 Fraud Detection using Machine Learning

 Overview

This project builds a machine learning model to detect fraudulent financial transactions using a large dataset. The goal is to accurately identify fraud while minimizing false positives.

 Approach

- Cleaned the dataset and removed unnecessary columns
- Created new features to capture balance inconsistencies
- Handled skewed data without removing important fraud signals

Model

- Used XGBoost Classifier
- Trained on 80-20 train-test split

Results

- High ROC-AUC score
- Strong precision and recall for fraud detection

 Key Insights

- Fraud mostly occurs in high-value transactions
- TRANSFER and CASH_OUT are high-risk transaction types
- Balance mismatches are strong fraud indicators

 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost

Conclusion

This project shows how machine learning can effectively detect fraud and help in proactive risk management.
