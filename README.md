# Churn-Prediction
Machine learning pipeline and predictive model to analyze customer churn, identify key attrition factors, and improve retention strategies using Python and scikit-learn.
# Customer Churn Prediction

Predicts which telecom customers are likely to leave, using the Telco Customer Churn dataset (7,043 customers).

## Key findings
- About 26.5% of customers churned.
- Baseline logistic regression caught 57% of churners (recall).
- With class balancing, recall rose to 78%, at the cost of more false alarms.
- Random Forest did not beat the simpler model, so I chose logistic regression for higher recall and easier explanation.
- Highest churn risk: fiber optic customers with short tenure and no long contract.

## Steps
1. Cleaned data (fixed TotalCharges, 11 blank values)
2. Encoded categories and scaled features
3. Compared logistic regression, balanced logistic regression, and Random Forest
4. Interpreted model coefficients

## Tools
Python, pandas, scikit-learn, Google Colab

## Dataset
Telco Customer Churn, from Kaggle (blastchar).
