# Road Accident Severity in Rainy Weather
Repository for Coursera Data Science Assignment

# Introduction
The goal of this project is to predict the severity of road accidents in rainy weather due to various conditions. This will help the community to stay safe and avoid damage or loss due to accidents in rainy weather. This will also help the Road Safety team to take necessary precautions.


# Data Understanding
By analysing the raw data, the following conclusion can be done.
Severity code is the target parameter or predictor variable which as it shows the severity of the accidents.
Data clean up is required as few columns are not required for analysis.
Since the goal is to get predictions for rainy weather, only rows corresponding to ‘Rainy’ Weather can be used.
ROADCOND and LIGHTCOND are different categories that can be derived from the Weather column.
Convert raw unbalanced data to balanced dataset.

# Methodology
- Defining variables X and Y
- Standardising the data set using scikit-learn
- Split Data into train and test set
- Modelling

# ML models used
1. K Nearest neighbor (KNN)
2. Decision Tree algorithm
3. Linear Regression Model


# Results
Accuracy of models on test data set
Following metrics can be used to evaluate a model.
1. Jaccard Index: It's a measure of similarity for the two sets of data, with a range from 0% to 100%
2. F1 score: The F-score, also called the F1-score, is a measure of a model’s accuracy on a dataset. 
3. Log loss: Log Loss quantifies the accuracy of a classifier by penalising false classifications.

# Python version  
3.6
