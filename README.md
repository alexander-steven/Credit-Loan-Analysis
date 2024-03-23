# Credit Loan Prediction and Analysis

This project was completed as the final task of the Project-Based Internship at ID/X Partners x Rakamin Academy which was conducted from October to November 2023.

Tools: Python, Jupyter Notebook, Numpy, Pandas, Matplotlib, Seaborn, Scikit-Learn

---
## Introduction

This project focuses on gaining insights and making predictions regarding clients who may have a probability of default by analyzing the previous customer's loan status from 2007 to 2014. This project aims to help lenders make decisions by avoiding loans with bad repayment histories.

## Data Preprocessing
- Feature Engineering
- Handling Duplicate Value
- Feature Encoding & Scaling
- Data Transformation
- Outlier Handling

## Data Modelling
Using the RandomForestClassifier Model, the model is tested with AUC-ROC and Kolmogorov-Smirnov as Evaluation Targets to find the optimal value. The result shows that the model goes to 84.5% for ROC and 53.6% for KS Score. In the credit risk modelling practice, AUC above 0.7 and KS above 0.3 are considered good performance. 

![image](https://github.com/alexander-steven/Credit-Loan-Analysis/assets/74502692/77bd3562-4abe-4ec0-8930-dc59c1c6b622)

![image](https://github.com/alexander-steven/Credit-Loan-Analysis/assets/74502692/01de089c-8176-424f-b04e-73f601807fa8)

## Business Insights and Recommendation

- By using a predictive model to make informed credit decisions, we can filter and select better borrowers for the credit loan as well as for risk assessment
- Adjust interest rate dynamically based on the probability of default, ensuring better, fairer and more accurate pricing for borrowers
- Implement strategies to address late payments near the end of loan terms for clients to improve timely repayment, for example: email reminders and client incentives.
- Create customer segmentations for different and unique client needs of their financing solutions.
- Provide comprehensive financial education and support programs to borrowers, empowering them to improve their financial literacy and repayment capabilities.
- Implement proactive collections strategies to minimize default risks and enhance loan recovery outcomes, ensuring a robust and efficient collections process.

---
Kind regards to Yanyan2410 for the references

