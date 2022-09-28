# Credit Risk Analysis

## Overview 
In recent years, obtaining personal loans has become one of the most popular and accessible options for millions of Americans to finance their lifestyles. Personal lending is growing faster than any other type of debt, whether it be credit card, auto, mortgage, or student debt. While it is such a growing finance trend that finance and banking institutions are providing to the public, it is key for them to understand the metrics and trends to optimize their lending practices. Or provide any insight for red flags of credit risk or fraud. 

In our analysis, we have a credit card dataset from LendingClub, a peer-to-peer lending services company, and through utilizing Python, we create and evaluate several machine learning models to predict credit risk. From the machine learning algorithms and our use of statistical reasoning, we will analyze the performance of the models and determine if there is the best one to focus on that will assist in predicting credit risk the most accurately. 

## Tools Used:
- Jupyter Notebook
- Python
- Google Colab

## Dataset:
- LoanStats_2019Q1.csv

## Objectives:
- Create training and test groups from a given data set.
- Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Compare the advantages and disadvantages of each supervised learning algorithm.
- Determine which supervised learning algorithm is best used for a given data set or scenario.
- Use ensemble and resampling techniques to improve model performance.

## Results
After applying the ETL process and splitting the data provided into training and test groups, we have a total of six algorithms and models to evaluate which one can bring us the most accurate responses to identifying an accurate credit risk. Here we have evaluated each model based on their respective balanced accuracy, precision, and recall scores. 

### Oversampling
**Naive Random Oversampling**

![naïve random oversampling](Images/naïve_random_oversampling.png)

- Balance Accuracy Score: 0.64132
- Precision Score (High/Low): 0.01/ 1.00
- Recall Score (High/Low): 0.60/ 0.68

**SMOTE Oversampling**

![smote oversampling](Images/smote_oversampling.png)

- Balance Accuracy Score: 0.63744
- Precision Score (High/Low): 0.01/ 1.00
- Recall Score (High/Low): 0.60/ 0.68

### Undersampling
**Cluster Centroids**

![cluster method](Images/cluster_centroids_undersampling.png)

- Balance Accuracy Score: 0.63744
- Precision Score (High/Low): 0.01/ 1.00
- Recall Score (High/Low): 0.61/ 0.45

**Combination (Over and Under) Sampling (SMOTEENN)**

![smoteenn method](Images/smoteenn_undersampling.png)

- Balance Accuracy Score: 0.52921
- Precision Score (High/Low): 0.01/ 1.00
- Recall Score (High/Low): 0.70/ 0.57

### Ensemble Learners
**Balanced Random Forest Classifier**

![brfc](Images/brfc_ensemble.png)

- Balance Accuracy Score: 0.78776
- Precision Score (High/Low): 0.04/ 1.00
- Recall Score (High/Low): 0.67/0.91 

**Easy Ensemble Classifier**

![eec](Images/eec_ensemble.png)

- Balance Accuracy Score: 0.91979
- Precision Score (High/Low): 0.07/ 1.00
- Recall Score (High/Low): 0.90/ 0.94

