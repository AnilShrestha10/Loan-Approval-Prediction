# Loan-Approval-Prediction

This repository contains code for building a loan prediction model using Python and several libraries such as NumPy, pandas, Matplotlib, Seaborn, and scikit-learn.

## Overview

The aim of this project is to predict whether a loan application will be approved or not based on various factors such as gender, marital status, education, income, loan amount, credit history, etc. We'll be using a dataset containing information about loan applicants.

## Dataset

The dataset (`loan.csv`) contains the following columns:

1. Loan_ID: Unique ID for each loan application
2. Gender: Gender of the applicant
3. Married: Marital status of the applicant
4. Dependents: Number of dependents
5. Education: Education level of the applicant
6. Self_Employed: Whether the applicant is self-employed or not
7. ApplicantIncome: Income of the applicant
8. CoapplicantIncome: Income of the co-applicant
9. LoanAmount: Amount of loan applied for
10. Loan_Amount_Term: Term of the loan in months
11. Credit_History: Credit history meets guidelines or not
12. Property_Area: Area where the property is located
13. Loan_Status: Whether the loan was approved or not

## Exploratory Data Analysis (EDA)

We begin by performing EDA on the dataset, which includes:

- Handling missing values
- Data visualization to understand the distribution and relationships between variables
- Preprocessing the data for modeling

## Model Building

We split the dataset into training and testing sets, preprocess the data, and then build a predictive model using Support Vector Machine (SVM) algorithm.
