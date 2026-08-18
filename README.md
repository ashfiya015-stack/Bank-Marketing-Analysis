# 📊 Bank Marketing Data Analysis

An exploratory data analysis and customer segmentation project using bank marketing campaign data to understand **customer behavior, marketing effectiveness, and term-deposit subscription patterns**.

## 🎯 Project Objective

The primary objective of this project is to analyze customer and marketing campaign data and identify factors associated with whether a customer subscribes to a term deposit.

The project focuses on:

* 👥 Customer demographics and behavior
* 📈 Marketing campaign effectiveness
* 🎯 Customer segmentation
* 💳 Loan and financial characteristics
* 📞 Contact methods and campaign frequency
* 📅 Campaign timing
* 🔍 Factors associated with term-deposit subscription

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```text
Bank-Marketing-Analysis/
│
├── Bank_Marketing_Inspection.ipynb
├── Bank_Marketing_Analysis.pptx
├── bankmarketing.csv
├── README.md
├── requirements.txt
│
└── images/
    └── visualizations/
        ├── Subscription Rate by Education.png
        ├── Subscription Rate vs No. of Campaign Contacts.png
        └── Term Deposit Subscription Rate.png
```

## 🔎 Analysis Performed

### 1. Dataset Inspection

* Dataset shape and structure
* Data types
* Missing-value analysis
* Duplicate analysis
* Descriptive statistics
* Numerical and categorical feature identification

### 2. Customer Demographics

The analysis examines subscription behavior across:

* Age groups
* Jobs
* Education levels
* Marital status

### 3. Financial & Loan Analysis

The project analyzes customer subscription behavior based on:

* Housing loan status
* Personal loan status
* Default status

### 4. Marketing Campaign Analysis

Campaign effectiveness is analyzed using:

* Contact method
* Number of campaign contacts
* Previous campaign outcome
* Contact month
* Contact day

### 5. Customer Segmentation

Customer segments are created using combinations of:

* Job
* Education

Segments with sufficient customer volume are compared based on their historical subscription rates.

### 6. Data Visualization

The project includes visualizations such as:

* Subscription distribution
* Age distribution
* Subscription rate by job
* Subscription rate by education
* Subscription rate by contact method
* Campaign-contact analysis
* Previous campaign outcome
* Loan analysis
* Monthly and weekly campaign performance
* Correlation heatmap

## 💡 Key Business Insights

The analysis is designed to help identify:

* Customer groups with relatively higher subscription rates
* More effective marketing contact methods
* The relationship between repeated campaign contacts and conversion
* The impact of previous campaign outcomes
* High-performing customer segments
* Better opportunities for targeted marketing

## 📌 Business Recommendations

Based on the analysis framework:

1. Prioritize customer segments with stronger historical subscription rates.
2. Focus marketing efforts on more effective contact methods.
3. Avoid excessive repeated contacts when conversion rates decline.
4. Use previous campaign outcomes to improve customer targeting.
5. Apply customer segmentation instead of using the same marketing strategy for every customer.

## 🤖 Machine Learning

The notebook imports machine-learning tools including:

* Logistic Regression
* Random Forest
* Label Encoding
* One-Hot Encoding
* Standard Scaling
* Train-Test Split
* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

These techniques can be used to build a predictive model for term-deposit subscription.

## 📁 Dataset

The project uses a bank marketing dataset containing customer attributes and marketing campaign information.

The target variable is:

```text
y
```

where the subscription outcome is represented as:

```text
yes / no
```

## 🚀 Future Improvements

* Build and compare multiple classification models.
* Perform feature importance analysis.
* Tune model hyperparameters.
* Handle class imbalance if required.
* Add an interactive Power BI dashboard.
* Deploy the prediction model using Streamlit.
* Create a customer-subscription prediction application.

## 👩‍💻 Author

**Ashfiya**

Aspiring Data Analyst | Machine Learning Enthusiast

---

⭐ If you find this project useful, consider giving the repository a star!
