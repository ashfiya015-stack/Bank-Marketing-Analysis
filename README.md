**Bank Marketing Analysis**
Predicting Term Deposit Subscription Using Machine Learning

**Overview**
This project analyzes customer data from a bank's marketing campaigns to understand which customer attributes and behaviors are most predictive of term deposit subscription. The goal is to help the bank target future campaigns more effectively by identifying customers most likely to subscribe.

#Objective
Analyze customer behavior and predict term deposit subscription using machine learning, enabling more efficient and targeted marketing campaigns.

**Dataset**
The dataset contains customer and campaign information typically including:
Demographic details (age, job, marital status, education)
Financial information (balance, housing loan, personal loan)
Campaign contact details (contact type, day, month, duration)
Previous campaign outcomes
Target variable: whether the customer subscribed to a term deposit

#Tools & Technologies
Language: Python
Data Handling: Pandas
Visualization: Seaborn, Matplotlib
Machine Learning: Scikit-learn
Environment: Jupyter Notebook

**Project Workflow**
Dataset → Data Cleaning → EDA → Visualization → ML Model → Prediction

1.Data Cleaning — Handling missing values, encoding categorical variables, and preparing the dataset for analysis
2.Exploratory Data Analysis (EDA) — Examining customer demographics, campaign patterns, and subscription trends
3.Visualization — Charting key relationships between customer attributes and subscription outcomes
4.Model Building — Training a Random Forest Classifier to predict subscription likelihood
5.Prediction — Generating predictions and evaluating model performance

**Machine Learning Model**
#Algorithm: Random Forest Classifier
Random Forest was selected for its ability to handle mixed data types (categorical and numerical), resist overfitting through ensemble averaging, and provide feature importance rankings — useful for explaining why a customer is likely to subscribe, not just predicting that they will.


#Features Delivered
Data cleaning and preprocessing pipeline
Exploratory data analysis with visualizations
Trained classification model for subscription prediction
Insights into key drivers of customer subscription behavior


**Project Structure**
Bank-Marketing-Analysis/
├── Bank_Marketing_Analysis.ipynb      # Main analysis & model notebook
├── bankmarketing.csv                  # Dataset
└── README.md


#Future Improvements
Add model evaluation metrics (accuracy, precision, recall, F1-score) directly to this README
Include visualizations (EDA charts, feature importance) as embedded images
Experiment with additional models (Logistic Regression, XGBoost) for comparison
Hyperparameter tuning to improve recall on the minority (subscribed) class
Deploy as a simple prediction interface (e.g. Streamlit app)

#Author
ASHFIYA
