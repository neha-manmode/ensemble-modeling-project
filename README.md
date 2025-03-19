Ensemble Modeling Project
📌 Project Overview
This project applies ensemble machine learning techniques to predict whether a bank customer will subscribe to a term deposit based on marketing campaign data.

🏦 Dataset: Bank Marketing Campaign Data
The dataset is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls, and the goal is to predict whether a client will subscribe (yes/no) to a term deposit.

📂 Data Features
Demographic Data: Age, job, marital status, education, etc.
Financial Information: Account balance, default status, housing loan, personal loan.
Campaign Data: Number of contacts, last contact month, duration of call, etc.
Previous Campaign Outcome: Previous interactions with the client.
🎯 Objective
To build a classification model that predicts whether a client will subscribe (yes/no) to a term deposit using ensemble learning techniques.

📊 Project Steps
Exploratory Data Analysis (EDA)

Shape and structure of data
Handling missing values and outliers
Summary statistics and visualizations
Data Preprocessing

Encoding categorical variables
Scaling numerical variables
Handling missing values
Model Training (Base Models)

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine
Ensemble Learning

Bagging (Random Forest, Bagging Classifier)
Boosting (AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost)
Stacking (Combining multiple models for better performance)
Model Evaluation

Accuracy, Precision, Recall, F1-score
ROC-AUC Curve, Feature Importance
Comparing base models vs ensemble models
