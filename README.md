Customer Churn Prediction using Machine Learning

📖 Overview



Customer churn prediction is a critical problem in the telecommunications industry, where companies aim to identify customers who are likely to discontinue their services. Retaining existing customers is more cost-effective than acquiring new ones, making churn prediction highly valuable.



This project applies multiple supervised machine learning algorithms to predict customer churn using a real-world dataset and compares their performance using evaluation metrics such as accuracy, recall, and F1-score.



🎯 Objectives

Predict whether a customer will churn or not

Compare multiple machine learning models

Evaluate model performance using appropriate metrics

Identify the most effective algorithm for churn prediction

📂 Dataset

Name: Telco Customer Churn Dataset

Source: Kaggle

Link: https://www.kaggle.com/blastchar/telco-customer-churn

📊 Dataset Details

Total records: 7043

Features: 21

Target variable: Churn (Yes/No → 1/0)

⚙️ Technologies Used

Python

Jupyter Notebook

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔄 Workflow

Data Loading

Data Cleaning

Handle missing values

Remove irrelevant columns

Data Preprocessing

Encoding categorical variables

Feature scaling

Model Training

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors

Model Evaluation

Accuracy

Recall

F1 Score

Confusion Matrix

Comparison \& Analysis

🤖 Machine Learning Models Used

Model	Description

Logistic Regression	Linear model for binary classification

Decision Tree	Tree-based classification model

Random Forest	Ensemble model using multiple trees

KNN	Distance-based classification

📊 Results

Model	Accuracy	Recall	F1 Score

Logistic Regression	0.78	0.49	0.55

Decision Tree	0.72	0.50	0.49

Random Forest	0.80	0.49	0.56

KNN	0.74	0.51	0.51

🔍 Key Insights

Random Forest achieved the best overall performance

Recall is relatively low across all models due to class imbalance

Accuracy alone is not sufficient for evaluation

📈 Visualizations

Model Accuracy Comparison

Recall Comparison

F1 Score Comparison

Confusion Matrix

⚠️ Challenges

Class imbalance in dataset

Difficulty in detecting churn customers

Model limitations in capturing complex patterns

🚀 Future Improvements

Apply SMOTE for handling class imbalance

Hyperparameter tuning (GridSearchCV)

Feature engineering

Try advanced models (SVM, XGBoost)

📁 Project Structure

├── data/

│   └── Telco-Customer-Churn.csv

├── notebook/

│   └── Customer\_Churn\_Analysis.ipynb

├── report/

│   └── ML\_Assignment\_Report.pdf

├── README.md

👨‍💻 Author



Keshan B K



📌 Notes

This project is part of a Machine Learning academic assignment

Dataset is publicly available

Code is implemented using Python and Scikit-learn

