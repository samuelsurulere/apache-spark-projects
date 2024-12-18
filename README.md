# apache-spark-projects
## Loan Prediction Model using PySpark
This project implements a machine learning pipeline for predicting loan approval status using PySpark. The model utilizes various classification algorithms to assess the likelihood of loan approval based on applicant information.

### Technologies Used
PySpark
Python
MLlib

## Data Processing
Load and inspect the loan dataset
Handle missing values using mean imputation for numeric columns and mode imputation for categorical columns
Feature engineering: Create a new 'TotalIncome' column
## Model Implementation
The project implements four classification models:
Logistic Regression
Random Forest
Decision Tree
Gradient Boosted Trees
## Results
Model performance (AUC scores):
Logistic Regression: 73%
Random Forest: 78%
Decision Tree: 67%
Gradient Boosted Trees: 80%
The Gradient Boosted Trees classifier achieved the highest AUC score of 80%, demonstrating superior performance in predicting loan approval status.
