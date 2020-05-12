# Project 2 - Ames Housing Data and Kaggle Challenge

Introduction

In this project, will explore the Ames, Iowa Housing Dataset
Here start by conducting some exploratory data analysis followed by processing the data based on the findings. The goal is ultimately to accurately create a regression model and this will predict the sales price of houses in the test set given the data in the training set

Table of Contents:
Discussion and Background
Cleaning and Visualizing data
Featuring matrix
Model Fitting
Model Evaluation
Prediction that model with given testing data
Findings and Recommendation of the project


Discussion and Background

Original dataset
- train.csv
- test.csv

Dataset documentation
From the documentation, we learn that the there are 2,051 observations and 82 variables, 

Import and Reading data:
Import all the followings to the Jupyter notebook

Import pandas
import numpy 
import seaborn as sns
import matplotlib.pyplot as plt
import LinearRegression
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.metrics import r2_score

Data Cleaning and Visualizing:
-Cleaning all null values and all.
-Plotting pair plot and correlation matrix to visualize and get the clear data
-Interaction of required features to get better score for the model

Featuring matrix:
-Train-test-split the data
-Featuring variables for X
-prediction is y variable ,here y is Sales price which we need to predict.
-scaling the data

Fitting Model and evaluation:
-Fitting respective features in a matrix and fit with model
-Evaluate the model by finding R2,RMSe,Cross validation of train and test data
-Did Hypothesis test to get that features are significanly differ or not 

Kaggle Submission:
Submitted my predicted .csv file to kaggle 
I submitted 13 predictions price with test data set ID

Final findings and Recommendations
-Showing recommendation in some features which  may shows impact on prediction variable

Submission:
On GitHub Enterprise submitted following submissions
-Technical Report(with 4 notebooks)
-Original datasets
-My datasets
_My README.md
-Presentation slides






