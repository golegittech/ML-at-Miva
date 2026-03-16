ML LAB ACCESSMENT

Objective 
To apply and compare different feature selection techniques and evaluate 
their impact on model performance. 
Task 
Using the Pima Indians Diabetes dataset, perform feature selection 
using the following techniques discussed in the lecture material 
(download the dataset from Kaggle) 
Instructions 
1. Dataset Preparation 
Load the dataset into Python. 
Separate the dataset into features XXX and target variable yyy. 
Perform any necessary preprocessing (e.g., handling missing values, 
feature scaling where required). 
2. Univariate Feature Selection 
Apply SelectKBest with the chi-squared (chi²) test. 
Select the top 4 features. 
Display the selected features and their scores. 
3. Recursive Feature Elimination (RFE) 
Use Logistic Regression as the base estimator. 
© Copyright 2025 MIVA Open University All Rights Reserved | 2 
Apply RFE to select the top 3 features. 
List the selected features. 
4. Principal Component Analysis (PCA) 
Apply PCA to reduce the dataset to 3 principal components. 
Report the explained variance ratio of each component. 
5. Feature Importance 
Train an ExtraTreesClassifier on the dataset. 
Compute and rank feature importance scores. 
Identify the top 3 most important features. 
6. Model Evaluation 
Train a Logistic Regression classifier using: 
- (a) All original features 
- (b) Features selected using Univariate Selection 
- Features selected using RFE 
- Compare classification accuracy for each case. 

Submission Requirements 
Python code (well-commented). 
Tables or printed outputs showing selected features and scores. 
© Copyright 2025 MIVA Open University All Rights Reserved | 3.

A brief discussion (5–7 sentences) comparing the results of the 
different feature selection techniques and their effect on model 
performance. 
Assessment Focus 
Correct application of feature selection methods 
Interpretation of outputs 
Clarity of results and discussion
