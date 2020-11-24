# sparkify Project

## Project Overview
This project aims to predict churn for users of a fictitious music application called Sparkify. The problem statement and the dataset is provided by Udacity. The dataset consist of logs of actions performed by any user who visits the application. The log is captured for each action across 18 columns for 226 users. We want to use this data to build ML model that predicts if a user will churn or not by using these attributes directly or through some transformation.

## Anlytics Pipeline

The solution is divided in following parts:
1. Data Exploration, Data Cleaning and Data Visualization
2. Feature Engineering
3. Model Building using Hyper-parameter tuning
4. Model Selection and Model Building

## Summary

We have succefully built an end-to-end analytics pipeline for predicting churn of users. We have used thorogh Data exploration to identify nulls, outliers, missing values and have done treatment of these using standard methods such as dropping rows, filtering. We have also analysed individual features with respect to churn variable to idenfy which variable is important and need to be retained for model building. For eg- Below plot shows that male churn more (24%) as opposed to female (18%). We have created 8 new features at user level which came significant during exploration and were intuitive. We have chosen two models - Logistic Regression and Random Forest- performed hyper-parameter tuning of these models using 3-fold cross validation on 80% Train set. Then we checked the model built on Test set. Based on the F1 score of the model on Test set we have chosen Random forest that showed F1 of 0.87. Below is the confuion matrix for the test set prediction using Random Forest. We have also validated our model using a 10% validation set.

## Result on Test and Validation Set

![alt text](http://url/to/img.png)
![alt text](http://url/to/img.png)


## Blog Link:
https://medium.com/@parsai.anu/sparkify-project-udacity-nanodegree-2b98949271ab


## libraries
1.pyspark.sql
2.pyspark.ml
3.matplotlib
4.pandas

## Files
Sparkify.ipynb- This file contains the analytics pipeline from Data Exploration to Model Building
