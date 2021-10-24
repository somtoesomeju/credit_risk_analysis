# credit_risk_analysis

## Purpose
The purpose of this project is to evaluate credit risk using machine learning. The dataset I will be using is the credit card user data from LendingClub, a credit lending services company. Using the dataset, I am going to analyze it using 6 different sampling methods (SMOTE, Naive Random oversampling, cluster centroid undersampling, SMOTEEN oversampling, Balanced random forest oversampling and Easy ensemble classifying oversampling). 

## Resources
- Software: Jupyter notebook 3.4.10
- Languages: Python

## Results
# SMOTE SAMPLING
In the SMOTE oversampling method, the balanced accuracy score was 62.3%.
- high risk precision is at 1%, while low risk precision is at 100%
- high risk recall is at 70%, while low risk recall is at 58%

# Naive Random Oversampling
- Balanced accuracy score was 64.56%
- high risk precision is at 1%, low risk precision 100%
- high risk recall is at 61%, while low risk recall is at 68%.

# Undersampling (Cluster centroid method)
- Balanced accuracy score was 62.3%
- high risk recall is at 61%, while low risk recall is at 45%.

# SMOTEEN Oversampling
- Balanced accuracy score was 52.9%
- High risk recall was 58% while low risk recall was at 70%.

# Balanced Random Forest Oversampling
- Balanced accuracy score was 74.4%.
- High risk recall was 60% and low risk recall was 89%

# Easy Ensemble Oversampling
- Balanced accuracy score was 91.1%
- High risk recall was 89% while low risk recall was 94%.


## SUMMARY
Six different sampling methods were used to analyze the data and produce the most accurate high risk credit results. From the methods, the most accurate sampling method is the easy ensemble oversampling method. I picked this method becuase it has the highest balanced accuracy score. It also has the most accurate high and low risk recall out of all the methods. 

