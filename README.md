# sparkify Project

The Sparkify project aims at prediction of churn of users of music application. The data provided contains log of user actions for a certain time period. The idea is to identify features that play a key role in users churning/cancelling the subscription of the application, so that we can use these features in the ML models and give churn predictions per user.
The data has been provided in 3 version of small, medium and big. We have chosen the small version that contains 286500 rows,18 columns and the project has been implemented using pyspark on Udacity platform.
The project is an application of entire data science pipeline on Big Data platform.
The data science pipeline is divided into 4 phases:
1. Data Cleaning and Outlier Treatment
2. Data Exploration & Churn Definition
3. Feature Engineering
4. Model Building & Validation

The data exploration helped us identify the below features for the model building-
1. Gender of User
2. Mean time spent by a user in a session
3. Number of artist listened to by a user
4. Mean time spent by a user in a item in a session
5. No. of time a user clicks on Next Song
6. No. of time a user click on Add to Playlist
7. No. of time a user clicks on Thumbs up
8. No. of times a user clicks on Thumbs down

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


