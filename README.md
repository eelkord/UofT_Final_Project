
=======
# UofT_Final_Project


=======
# LOAN APPROVAL PREDICTION USING MACHINE LEARNING MODELS

## Primary Objectives:

Primary Objectives:
The primary objective is to predict if the loan status of the applicant has been approved or not. For this project, we take on the role of financial analyst for a finance company to build our model to predict the outcome of the loan status of customers using different data values. For this project, we will use the classification model in which we need to classify whether the loan will be approved or not. classification refers to a predictive modeling problem where a class label is predicted for a given example of input data.

Business problem:
We work for a finance company that deals in all kinds of home loans. Usually, an applicant first applies for a home loan and after that, the company validates the customer's eligibility for the loan. We aim to automate the loan eligibility process (real-time) based on customer details provided while filling out online application forms. These details are:

Gender,
Marital Status,
Education,
number of Dependents, I
Income,
Loan Amount,
Credit History,
and others.

## Data source

- Raw data   https://finalprojectanalysis-bucket.s3.us-east-2.amazonaws.com/loan_application_dataset+(version+1).xlsb+.csv

- Cleaned data : : https://finalprojectanalysis-bucket.s3.us-east-2.amazonaws.com/clean_data.csv

## Data cleaning:

To perform our EDA we used a common notebook to clean our dataset. We stored our raw dataset on AWS and read it as dataframe and performed multiple codes to clean our data 

Please click [here](https://github.com/eelkord/UofT_Final_Project/blob/main/Clean%20data.ipynb) to go to notebook used to clean our dataset.

## EDA and Tableau

To perform our exploratory data analysis we had to explore each column and told a story with our dataset. 
Please click [here](https://github.com/eelkord/UofT_Final_Project/blob/fofomichelle/exploratory_analysis.ipynb) to go the code that was used to perform the analysis

For instance we we did a bar chart on education and discovered that part of our applicants were graduates as opposed to the ones that were not graduate.
![image](https://user-images.githubusercontent.com/99924850/181996284-6d8b5428-07ae-4abf-a494-5fd71bcb86ce.png)
We then established a relationship between our different features with the target output
Finally we performed a correlation between all our features to help while doing our machine learning part of the analysis identify which features will be more important
![image](https://user-images.githubusercontent.com/99924850/181996216-86000c0a-77cc-44ca-b152-5c6c7f103991.png)

To better visualize our dataset and tell a better a story with our dataset we used Tableau and created almost the same relations if not better ones. Please click [here](https://public.tableau.com/app/profile/reno4875/viz/LoanApprovalWorkbook/Story1) for details about the story created in Tableau.

## Machine Learning

For our machine learning parts we used 3 models : LogisticRegression,Decision Tree Model, Random Forest and Gradient Boosting. Please click [here](https://github.com/eelkord/UofT_Final_Project/blob/karishmasnh/Refactored%20and%20featured%20code%20-v3.ipynb) for more details about the codes used for each model 
Below are the results of our models
- Logistic Regression
![image](https://user-images.githubusercontent.com/99924850/181996515-a647b55d-5d67-4b39-97f7-933e759d4a12.png)

- Decision Tree

![image](https://user-images.githubusercontent.com/99924850/181996543-52ddfdff-207c-43f9-b2b3-23951c42c064.png)

- Random Tree

![image](https://user-images.githubusercontent.com/99924850/181996572-34812e95-f1ae-4454-a4ef-037ee17fcbbc.png)

- Gradient Boost


![image](https://user-images.githubusercontent.com/99924850/181996587-1a177a2b-19fb-4aa4-a657-a5acb29530be.png)

As you can see the machine learning model which had a higher accuracy score is the logistic regression Model so we will be using the later to run our prediction analysis. 
Please do click [here](https://github.com/eelkord/UofT_Final_Project/blob/karishmasnh/Description%20of%20ML%20model.docx) for more information on how the machine learning was processed.







=======



