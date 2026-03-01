Bank Marketing Campaign Optimization using Machine Learning

Project Overview

This project builds an industry-level machine learning pipeline to predict whether a customer will subscribe to a term deposit.
The goal is to optimize marketing campaigns by identifying high-probability customers while minimizing unnecessary calls.

Dataset

Source: UCI Machine Learning Repository  
Dataset: Bank Marketing (bank-additional-full.csv)  
Records: 41,188 customers  

Business Objective

- Increase subscription conversion rate
- Reduce marketing cost
- Improve targeting efficiency

Models Used

- Decision Tree (Baseline)
- Random Forest (Final Model)

Final Model Performance (Random Forest)

- Accuracy: ~87%
- Recall (Subscribed): 68%
- ROC-AUC: 0.76
- Threshold Optimization: 0.4 (Business Balanced Strategy)

Key Insights

- Economic indicators strongly influence subscription behavior.
- Previous successful campaigns increase probability of conversion.
- Excessive campaign contact reduces effectiveness.
- Age and employment conditions affect customer decisions.

Business Impact

Using threshold tuning:

- Improved customer detection from 25% → 68%
- Increased projected campaign profitability
- Reduced unnecessary marketing calls

Technologies Used

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## 👩‍💻 Author

Nayana Goudar
