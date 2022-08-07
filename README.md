
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

To better visualize our dataset and tell a better a story with our dataset we used Tableau and created almost the same relations if not better ones.
We then created different dashboards and stories for a better visualization and to learn more about our dataset. 
Please click [here](https://public.tableau.com/app/profile/reno4875/viz/LoanApprovalWorkbook/Story1) for details about the story created in Tableau.

## Machine Learning

For our machine learning parts we used 4 models : LogisticRegression,Decision Tree Model, Random Forest and Gradient Boosting. Please click [here](https://github.com/eelkord/UofT_Final_Project/blob/karishmasnh/Refactored%20and%20featured%20code%20-v3.ipynb) for more details about the codes used for each model 

Explanation of model choice, including limitations and benefits
This is a classification problem with binary output so Logistic regression, Decision trees and Random Forest classier can be utilized to analyse the model (supervised learning) can be used. If none of the models gives the right results then, Gradient Boost can be used to improvise.
11:44
Description of preliminary feature engineering and preliminary feature selection, including their decision-making process
First, looking at the statistics to identify if some the features had a large spread that required standardizing and scaling.
Look at the EDA to identify outliers and correlation amongst the features.
Remove the outliers
Create a new column of Total Income from summing Applicant Income and Co Applicant Income
Encode the various categorical features using get dummies
Encode the Loan_Status feature i.e. our outcome column using Label Encode since the output needs to be encoded in one single column
Also looked at the Class imbalance with the Counter formula.
Minority class was 30% so used Oversampler to remove the class imbalance.
Since some of the columns like Applicant Income had a huge range so used Standard scaler to scale and fit.

Below are the results of our models
- Logistic Regression
![image](https://user-images.githubusercontent.com/99924850/183312168-7ab31eb0-6aca-49ae-a269-b7d428a82609.png)


- Decision Tree

![image](https://user-images.githubusercontent.com/99924850/183312485-db3570e6-396a-4838-bb96-fb7aacaaa41c.png)

- Random Tree

![image](https://user-images.githubusercontent.com/99924850/183312401-66b5df66-5fb4-4454-a044-2738f252c0d1.png)

- Gradient Boost


![image](https://user-images.githubusercontent.com/99924850/183312521-33597602-2861-4427-98c8-69e6ba5a56a8.png)

This is a classification problem with binary output so Logistic regression, Decision trees and Random Forest classier can be utilized to analyse the model (supervised learning) can be used. If none of the models gives the right results then, Gradient Boost can be used to improvise.

Please do click [here](https://github.com/eelkord/UofT_Final_Project/blob/karishmasnh/Description%20of%20ML%20model.docx) for more information on how the machine learning was processed.


## Presentation

After conducting our analysis we have then summarized our analysis into a google side presentation which will be used to present our analysis to different stakeholders of the financial company that requested the analysis.
Please click [here](https://docs.google.com/presentation/d/1bvOXDqs_5ezLtgVh4gu2DeZsfNF7g01j4ui4nQoCLyA/edit#slide=id.g1428059bb69_2_64) to access the presentation.





=======



