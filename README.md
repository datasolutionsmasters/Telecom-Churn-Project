# Telecom-Churn-Project
One of the Major Client of Rubixe

Telecom Churn Rate ML ProjectProject Report

Project Summary
No-Churn Telecom is an establish Telecom operation in Europe with more than a decade in Business. Due to new players in the Market, telecom industry has become very competitive and retaining customers becoming challenge. In spite of No-Churn initiative for reducing tariffs and promoting more offers, the churn rate (percentage of customers migrating to competitors) is well above 10%.
No-Churn wants to explore possibility of Machine Learning to help with following use cases to retain competitive edge in the industry.

Problem Definition
1. No-Churn Telecom has churn rate of above 10% which is not healthy to
company’s sustainability.
2. The factors affecting the churn rate is not clear.
Predicting customers with high churn possibility can significantly help no-churn telecom to reduce the churn rate through targets campaigns and offers.
The proposed Machine Learning algorithm is expected to predict the customers with high churn probability and flag them as “CHURN” along with churn score.

THE TARGET FUNCTION / VARIABLE
Target Variable: churn

FEATURE REPRESENTATION
Two features are dropped
State -> as another feature ‘area code’ captures the state
Phone -> is phone number which is not valid feature for ML model.

Data Preparation
Data has no missing values or format issues. Not much Data Preparation was done.Data taken to further step as is.
5 EDA – Exploratory Data Analysis
6 Model Evaluation / Testing Results
1 THE DATA SETS
Train Data Set size: 3462
Test Data Set size: 1154
2 LEARNING

Logistic Regression algorithm achieved a perfect accuracy score of 100% There by no further experiment required.
3 RESULTS & DATA ANALYSIS
7 Re-training and Future Work

As this model after implementation changes the business and customer perception thereby changing the churn rate factors.
It is advised to re-train the model every month for next one year.


8 Model Deployment
All features were taken as predictors expect [State] and [Phone]
Only three features were label encoded
Int_plan : NO -> 0, Yes -> 1
Vmail_plan : NO -> 0, Yes -> 1
Churn : False -> 0, True -> 1
Model deployment team should be labelling the input for predicting model
accordingly.

Conclusion
This Machine Learning algorithm can predict 100% of the probable churn
customers. No-Churn Telecom can run targeted campaigns with lucrative offers to retain the customers thereby reducing churn rate.
Project Objective is to achieve high accuracy prediction model, so this project met and exceeded the customer expectation.
The benefits of reducing churn rate below 5% is not only related to predicting but also based on effectiveness of retention campaigns. The benefits achievement can’t be attributed to project success. The results of retention campaigns should be analyzed explicitly to improve the benefits realization. 
