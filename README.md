# AI-Powered-Late-Delivery-Prediction-System-for-Talabat-UAE

## OVERVIEW

AI-based system predicting delivery delays for Talabat (UAE's leading food delivery platform). Uses machine learning to forecast whether an order will be delayed and how severe the delay will be, enabling proactive interventions before delays occur.

## WHAT IT DOES

### TASK 1 - Classification
- Goal: Will order be delayed? (Yes/No)
- Models Used: Logistic Regression, Random Forest, Naive Bayes, KNN

### TASK 2 - Regression 
- Goal: How many minutes late?
- Models Used: Linear Regression, Elastic Net, Random Forest, XGBoost

## KEY RESULTS 

### TASK 1 - Classification Performance 
- Best Model: Naive Bayes (78.86% accuracy)
- High-risk segment: Top 10% orders have 2.25x higher delay rate (50.4% vs 22.4% baseline)

### TASK 2 - Regression Performance 
- Best Model: Random Forest Regressor (MAE: 4.70 minutes)
- Predicts delay severity within ~ 5 minutes margin

## TECH STACK 

- Python (pandas, scikit-learn, xgboost)
- Google Colab
- GridSearchCV for hyperparameter tuning

## FILES 

- 'CSCI323_Project_Report.pdf' - Full project documentation

## DISCLAIMER
**This repository is for viewing purposes only. The code is not licensed for copying, modification, or commercial use without explicit permission from the author.**
