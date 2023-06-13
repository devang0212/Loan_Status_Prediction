# Loan_Status_Prediction

#### Here we are going to solve the Loan Approval Prediction. It is a classification problem in which we need to classify whether the loan will be approved or not.


## Table of Contents

- Introduction
- Business Problem
- Importing Modules
- Dataset Analysis
- Handling Missing Values - Categorical & Numerical
- Outliers Detection & Handling
- Analysis Categorical Data with Target
- Data Preparation
- Handling Imbalance Data
- Creating Multiple Model & choosing the best-suited model
- Model Building


## Problem Statement

Automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. The details include gender, marital status, education, number of dependents, income, loan amount, credit history, and others.

The major aim of this notebook is to predict which of the customers will have their loan approved.


## Features of Dataset

- LoanID = Unique Loan ID
- Gender = Male/ Female
- Married = Applicant married (Y/N)
- Dependents = Number of dependents
- Education = Applicant Education (Graduate/ Under Graduate)
- SelfEmployed = Self-employed (Y/N)
- ApplicantIncome = Applicant income
- CoapplicantIncome = Coapplicant income
- LoanAmount = Loan amount in thousands
- LoanAmountTerm = Term of the loan in months
- CreditHistory = Credit history
- PropertyArea= Urban/ Semi-Urban/ Rural
- LoanStatus = (Target) Loan approved (Y/N)


## Skills
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Model : KNeighborsClassifier, SVC, DecisionTreeClassifier, LogisticRegression, GaussianNB, RandomForestClassifier
- Best Model: LogisticRegression
- [ Logistic regression can be used for our model as its giving effective training testing accuracy ]
