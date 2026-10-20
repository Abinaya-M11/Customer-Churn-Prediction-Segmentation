# Customer Churn Prediction & Segmentation

## Project Overview

This project focuses on analyzing customer behavior, predicting customer churn, and segmenting customers based on their characteristics and purchasing patterns. By combining SQL, Python, and machine learning, the project identifies churn trends and generates actionable insights to support customer retention strategies.

## Objectives

- Analyze customer demographics, subscription details, and billing information.
- Perform SQL-based analysis to identify churn patterns.
- Conduct Exploratory Data Analysis (EDA) to uncover key customer trends.
- Perform feature engineering to improve customer behavior analysis.
- Build a machine learning model to predict customer churn.
- Segment customers using K-Means clustering.
- Develop data-driven recommendations to improve customer retention.

## Tech Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Database & Queries:** SQLite, SQL
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Algorithms:** HistGradientBoostingClassifier, Random Forest, K-Means Clustering
- **Environment:** Jupyter Notebook

## Dataset

The project uses the Telco Customer Churn dataset, which contains customer demographics, service subscriptions, contract information, payment methods, monthly charges, total charges, and churn status.

**Dataset file:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## Project Workflow

### 1. Data Cleaning and Preprocessing
- Loaded the dataset using Pandas.
- Converted numerical columns into appropriate data types.
- Handled missing values.
- Encoded the target variable for machine learning.

### 2. SQL-Based Analysis
- Queried customer data using SQLite.
- Analyzed churn across contract types and payment methods.
- Examined customer charges and revenue-related patterns.
- Identified customer groups requiring further investigation.

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer churn distribution.
- Investigated relationships between churn, tenure, and monthly charges.
- Compared churn patterns across customer and service categories.
- Created visualizations using Matplotlib and Seaborn.

### 4. Feature Engineering
- Created additional features to represent customer behavior.
- Analyzed spending patterns and service usage.
- Prepared features for predictive modeling and customer segmentation.

### 5. Customer Segmentation
- Applied K-Means clustering to group customers into four segments.
- Examined customer characteristics across the resulting clusters.
- Identified opportunities for targeted customer engagement and retention.

### 6. Churn Prediction
- Prepared categorical and numerical features.
- Applied encoding and feature scaling where appropriate.
- Developed a classification workflow using Scikit-learn.
- Evaluated model performance using classification metrics and a confusion matrix.
- Examined feature importance using Random Forest.

### 7. Business Recommendations
- Improve onboarding and engagement for new customers.
- Encourage suitable long-term subscription plans.
- Develop personalized retention campaigns.
- Explore service bundles and convenient payment options.
- Use customer segmentation to prioritize retention efforts.

## Key Deliverables

- SQL queries for customer churn analysis.
- Data cleaning and preprocessing workflow.
- Exploratory data analysis visualizations.
- Engineered customer behavior features.
- Four customer segments using K-Means clustering.
- Machine learning classification workflow.
- Feature importance analysis.
- Business recommendations for customer retention.

## Business Impact

The project demonstrates how data analytics and machine learning can help businesses understand customer churn, identify behavioral patterns, segment customers, and develop targeted retention strategies.

## Future Enhancements

- Develop an interactive Power BI dashboard.
- Compare multiple classification algorithms.
- Evaluate models using ROC-AUC and other performance metrics.
- Build a customer churn risk scoring system.
- Deploy an interactive application for exploring customer segments.

## Skills Demonstrated

Python | SQL | Data Cleaning | Exploratory Data Analysis | Feature Engineering | Machine Learning | K-Means Clustering | Data Visualization | Business Analytics | Customer Retention

