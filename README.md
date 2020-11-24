# sparkify Project

This project aims to predict churn for users of a fictitious music application called Sparkify. The problem statement and the dataset is provided by Udacity. The dataset consist of logs of actions performed by any user who visits the application. The log is captured for each action across 18 columns for 226 users. We want to use this data to build ML model that predicts if a user will churn or not by using these attributes directly or through some transformation.

Summary:
We have successfully built a churn prediction model using Random Forest with validation accuracy of 89% and F1 of 0.86. Our solution takes the log information, cleans it and transforms it into new features at user level. It then uses RF to make Churn/No Churn Classification at user level.

Blog Link:
https://medium.com/@parsai.anu/sparkify-project-udacity-nanodegree-2b98949271ab


Following libraries have been used in the project:
1.pyspark.sql
2.pyspark.ml
3.matplotlib
4.pandas

The following file present in the repository:
Sparkify.ipynb- This file contains the analytics pipeline from Data Exploration to Model Building
