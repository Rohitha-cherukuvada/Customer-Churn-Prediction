# Customer-Churn-Prediction
Telecommunication Customer Churn Forewarning

Project Description  

And so we created this project to forewarn customers churn for a defined telecommunication company. The purpose is to find customers on the verge of churn using features like account info, usage stats, and customer demographics. The approach followed in this project utilizes Random Forest Classifier.

Dataset 

The dataset for this project includes pieces under customer data as:  

- Account information: Subscription-based account tenure.  

- Customer activity: Call minutes, data traffic.  

- Demographics: Gender, age, where he/she resides, etc.  

- Target attribute: Indicating customer churn (0: No, 1: Yes).  

Actions Taken  

1. Data Cleaning  

- Missing Value Management (imputation).  

- Applied appropriate data types for each column.  

- Removed duplicates.  

- Coded categorical features.  

- Normalized numerical features to ensure better performance.  

2. Data Visualization  

- Analyzed and plotted distribution for important metrics.  

- Investigated relationships among variables.  

- Checked target variable skew.  

3. Creating Models  

- Created model with Random Forest Classifier.  

- Adjusted hyperparameters to maximize performance.  

4. Assessment  

- Evaluated with accuracy, confusion matrix, and F1 score.  

- Improved class distribution with SMOTE for better performance.  

5. Model Saving  

- The created model was exported with joblib for further usage.

Achieved accuracy of 80%.
