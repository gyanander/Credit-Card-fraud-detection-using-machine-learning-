## Credit Card Fraud Detection using Machine Learning

## Project Overview:
                    This Project focuses on detecting fraudulent credit card transaction using Machine Learning techniques.
                    The main objective is to build a reliable fraud detection system by performing data preprocessing ,handling
                    imbalanced data ,training multiple machine learning models and evaluating their performance.

## Tools & Libraries
- Python
- Pandas
- Numpy
- MAtplotlib
- Seaborn
- Scikit-Learn
- Joblib

 ## Dataset information
 - Total Records:57,434
 - Features:30
 - Target Variable:Class
 - Class 0 = Normal transaction
 - Class 1 = Fraudulent Transaction

 ## Data Preprocessing
 - Loaded the dataset
 - Checked datset shape and information
 - Identified missing values
 - Removed missing values
 - Detected duplicate records
 - Removed duplicate records
 - Standardized Amount feature using StandardScaler

## Exploratory Data Analysis (EDA)
- Dataset overview
- Class distribution analysis
- Missing value anlysis
- Duplicate Data Analysis
- Correlation anlysis
- Data visualtization
- Fraud vs Normal transaction comparison

## Handling Imbalanced Dataset
The Dataset was highly imbalanced.
Techniques applied:
- Undersamplimg
- Balanced dataset creation
- Class distribution verification

## Machine Learning Model used
###Logistic Regression
Performance Metrics:
- Accuracy: 97.56%
- Precision:97.29%
- Recall: 100
- F1 Score: 98.63%

## Decision Tree Classifier
### Performance Metrics:
- Accuracy:90.24%

 ## Random Forest Classifier
- ### Performance Metrics:
- Accuracy: 100%
  Random Forest achieved the highest performance amomg all models.

## Model Evaluation Metrics
The following evaluation metrics were used:
- Accuracy Score
- Precision Score
- Recall Score
- F1 Score

## Model Comparison
Model                        Accuracy
Logistic Regression          97.56%
Decision Tree                90.24%
Random Forest                100%

## Model Saving
The Final Random Forest model was saved using Joblib.


- 
##
 - 
  
