# Titanic Survival Prediction with AWS Sagemaker

## Project Objective
1. Use a major Big Data system to perform a Data Engineering related task
2. Example systems could be: (AWS Athena, AWS Spark/EMR, AWS Sagemaker, Databricks, Snowflake)

## Problem Statement
The titanic project is based on the scenario of the actual titanic ship that took passengers for a sea trip, and never returned back. 

This project focuses on predicting the passenger survival based on the different features available in the dataset.

We are going to train and test our model in this project.


## Dataset
Titanic Survival Dataset Competition (link: https://www.kaggle.com/competitions/titanic)

Column of the Dataset:
![Dataset Preview](https://github.com/nogibjj/project4-lyk/blob/main/Dataset%20Sample.png)


## Conceptual Model
![Conceptual Model](https://github.com/nogibjj/project4-lyk/blob/main/Conceptual%20Model.png)

## To-do List
1. Upload dataset to AWS S3 buckets

![S3 data](https://github.com/nogibjj/project4-lyk/blob/main/S3%20Data.png)

2. Create Notebook Instance in AWS Sagemaker

![Sagemaker Notebook](https://github.com/nogibjj/project4-lyk/blob/main/Sagemaker%20Notebook.png)

3. Load data from S3 buckets

![Load data](https://github.com/nogibjj/project4-lyk/blob/main/Load%20Data.png)

4. Visual Data Exploration

![Visual data](https://github.com/nogibjj/project4-lyk/blob/main/Visual%20Data.png)

5. Data Cleaning

  a. Extract the Name Titles (Mr, Mrs etc) from the Name feature field

  b. Change the Gender to numeric values

  c. Fill the missing info in dataset

  d. Drop Unwanted Columns

6. Train the model

![Training Code](https://github.com/nogibjj/project4-lyk/blob/main/Training%20Code.png)

![Training Jobs](https://github.com/nogibjj/project4-lyk/blob/main/Train%20job.png)

7. Deploy the Model

![Model](https://github.com/nogibjj/project4-lyk/blob/main/Model.png)

![End Point](https://github.com/nogibjj/project4-lyk/blob/main/Endpoint.png)

8. Survival Prediction

![Predictions](https://github.com/nogibjj/project4-lyk/blob/main/Predictions.png)

## Reference
* [Watch on YouTube](https://www.youtube.com/watch?v=oGGIeDh51ZQ&list=PLATp91001ydZ71zg8rJ0vPGZ6GzAeMnD4&index=1&t=218s)
