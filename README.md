📊 CreditWise – Loan Approval Prediction System
🔍 Project Overview

CreditWise is a Machine Learning–based Loan Approval Prediction project developed using Python (Jupyter Notebook).
The system predicts whether a loan application should be Approved or Rejected based on applicant financial and demographic details.

Multiple ML models were trained and evaluated, and the best model was selected based on Precision score, making the system more reliable for real-world loan approval scenarios where false approvals are costly.

🎯 Problem Statement

Financial institutions receive thousands of loan applications daily.
Manual evaluation is:

Time-consuming

Error-prone

Biased

This project aims to automate loan approval decisions using Machine Learning to improve accuracy and efficiency.

🛠️ Technologies Used

Language: Python

Environment: Jupyter Notebook

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

📁 Dataset Description

The dataset contains historical loan application data with the following features:

Gender

Married

Dependents

Education

Self Employed

Applicant Income

Coapplicant Income

Loan Amount

Loan Amount Term

Credit History

Property Area

Loan Status (Target Variable)

🔄 Project Workflow
1️⃣ Data Loading & Understanding

Loaded dataset using Pandas

Checked data shape, column types, and missing values

2️⃣ Data Preprocessing

Handled missing values

Encoded categorical variables

Prepared features and target variable

3️⃣ Exploratory Data Analysis (EDA)

Visualized distribution of key features

Analyzed relationship between Credit History and Loan Status

Identified important patterns influencing loan approval

4️⃣ Model Building

The following Machine Learning algorithms were implemented:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Dataset was split into training and testing sets before model training.

📊 Model Evaluation & Selection

Each model was evaluated using:

Accuracy

Precision

Recall

F1-score

✅ Model Selection Criterion

👉 Precision Score was used as the primary metric for selecting the best model, since:

In loan approval systems, false positives (wrong approvals) are more risky than false rejections.

📌 The model with the highest Precision score was selected as the final model.

📈 Results & Insights

All three models performed reasonably well

Credit History emerged as the most influential feature

Precision-based evaluation helped identify the most reliable approval model

The selected model minimizes incorrect loan approvals..
