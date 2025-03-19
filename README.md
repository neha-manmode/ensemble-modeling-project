# 🎯 Ensemble Modeling Project

## 📌 Project Overview
This project applies **ensemble machine learning techniques** to predict whether a bank customer will subscribe (`yes`/`no`) to a term deposit. We leverage **Bagging, Boosting, and Stacking** techniques to improve model performance.

## 📊 Dataset: Bank Marketing Campaign Data
The dataset contains information on **customer demographics, financial attributes, and marketing campaign interactions**. The goal is to analyze these features and build a predictive model.

### 🏦 **Dataset Features**
- **Customer Information:** Age, job type, marital status, education level
- **Financial Status:** Account balance, default history, housing and personal loans
- **Campaign Details:** Number of contacts, contact month, last contact duration
- **Previous Campaign Results:** Previous interactions and their outcomes
- **Target Variable (`y`)**: Whether the client subscribed to the term deposit (`yes` or `no`)

## 🚀 **Project Workflow**
### **Step 1: Exploratory Data Analysis (EDA)**
✔ Data summary & visualization  
✔ Missing values & outliers handling  
✔ Feature correlations  

### **Step 2: Data Preprocessing**
✔ Encoding categorical variables  
✔ Scaling numerical variables  
✔ Feature selection  

### **Step 3: Model Training**
✔ **Base Models:** Logistic Regression, Decision Tree, Random Forest, SVM  
✔ **Ensemble Learning:**  
   - ✅ Bagging (Random Forest, Bagging Classifier)  
   - ✅ Boosting (AdaBoost, Gradient Boosting, XGBoost, LightGBM)  
   - ✅ Stacking (Combining multiple models)  

### **Step 4: Model Evaluation**
✔ Accuracy, Precision, Recall, F1-score  
✔ ROC-AUC Curve & Feature Importance  
✔ Compare Base Models vs. Ensemble Models 
