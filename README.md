# UofT_Final_Project
# LOAN APPROVAL PREDICTION USING MACHINE LEARNING MODELS

## Primary Objectives:

The primary objective is to predict if the loan status of the applicant has been approved or not. For this project, we take on the role of financial analyst for a finance company to build our model to predict the outcome of the loan status of customers using different data values. 
 For this project, we will use the classification model in which we need to classify whether the loan will be approved or not. classification refers to a predictive modeling problem where a class label is predicted for a given example of input data.
 
 ## Business problem:
 
 We work for a finance company that deals in all kinds of home loans. Usually, an applicant first applies for a home loan and after that, the company validates the customer's eligibility for the loan.
We aim to automate the loan eligibility process (real-time) based on customer details provided while filling out online application forms. These details are:

 - Gender, 
- Marital Status,
- Education, 
- number of Dependents, I
- Income, 
- Loan Amount, 
- Credit History,
- and others.

## Data source
Kaggle

### About the dataset:

We have two CSV files which are labeled as train and test data. The train and test dataset would have the same columns except for the target column are “Loan Status”.

![image](https://user-images.githubusercontent.com/99924850/179431647-28e8d08d-f2bf-43a8-98dd-e5714eb08620.png)

Loan status can have two values: Yes or NO.

**Yes**: if the loan is approved

**NO**: if the loan is not approved

We will use the training dataset to train our model and try to predict our target column which is “Loan Status” on the test dataset.
We will use the training set to build our model and the test dataset to validate it. Both files are stored as CSV files.

## TECHNOLOGY
 We will use Pandas and Python to clean the data.
Then we will use MongoDB and PostgreSQL for database storage.
Machine Learning using linear regression will be used to predict loan application status.
Finally, the dashboard to visualize the findings and outcome will be using Tableau.

Below is a screenshot of the ERD

![image](https://user-images.githubusercontent.com/99924850/179431729-97e818f1-4e1b-4726-86ba-2dcf37d18c76.png)










