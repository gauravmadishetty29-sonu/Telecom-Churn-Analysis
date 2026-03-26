# Telecom Customer Churn Analysis

## Project Overview
This project focuses on analyzing telecom customer data to understand churn behavior and identify patterns that can help improve customer retention.
The goal is not only to build a predictive model but also to extract meaningful insights from data and support business decision-making.

## Objectives
- Analyze customer behavior and usage patterns  
- Identify factors influencing churn  
- Perform data cleaning and preprocessing  
- Build basic predictive models  
- Segment customers based on churn risk  

## Dataset
The dataset contains telecom customer information such as:
- Customer demographics  
- Call, SMS, and data usage  
- Registration details  
- Churn status (Target Variable)

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## Steps Performed

### 1. Data Cleaning
- Handled missing values using median and mode  
- Converted date columns into usable format  

### 2. Feature Engineering
- Created new features like:
  - Usage intensity  
  - Engagement score  
  - Customer tenure  

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer behavior patterns  
- Visualized key relationships using plots  

### 4. Model Building
- Applied machine learning models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  

### 5. Model Evaluation
- Evaluated models using:
  - ROC-AUC Score  
  - Confusion Matrix  
  - Classification Report  

## Key Finding

All models resulted in ROC-AUC scores close to **0.5**, indicating:

- Weak relationship between features and churn  
- Lack of strong predictive signal in the dataset 

## Customer Segmentation

Customers were categorized into:
- 🔴 High Risk  
- 🟡 Medium Risk  
- 🟢 Low Risk  

This helps businesses prioritize retention strategies.

##  Model Explainability

- Used SHAP (SHapley Additive Explanations)
- Identified feature importance and impact on predictions  

## Business Insights

- Customer usage features alone are not sufficient to predict churn  
- Additional data like customer complaints, billing, and service issues is required  
- Data-driven segmentation can still support business decisions  

## Future Improvements

- Include more relevant customer behavior features  
- Use time-series analysis  
- Try advanced models with better data  
- Improve feature selection techniques  

## Key Learnings

- Data quality is more important than model complexity  
- Feature engineering plays a critical role  
- Not all datasets are suitable for prediction tasks  
- Business understanding is essential in data science  

##  Conclusion

This project demonstrates an end-to-end data analysis workflow and highlights real-world challenges in predictive modeling.

##  Author
Gaurav Madishetty  
Aspiring Data Analyst / Data Scientist
