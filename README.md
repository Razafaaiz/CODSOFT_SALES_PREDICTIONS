# CODSOFT_SALES_PREDICTIONS
Project Overview
---------------------------------------------------------------------------------------------
The Sales Prediction project leverages data science and machine learning techniques in Python to predict the car purchase amount that customers are likely to spend. The prediction is based on various customer attributes, including age, annual salary, credit card debt, net worth, and other factors. Accurate predictions of car purchase amounts allow businesses to optimize their advertising strategies and maximize their sales potential.
-----------------------------------------------------------------------------------------------
Objectives
--------------------------------------------------------------------------------------------------
The main objectives of this project are as follows:

Build a machine learning model to predict car purchase amounts based on customer attributes.
Evaluate the model's performance and accuracy.
Provide insights to help businesses optimize their advertising strategies and maximize sales potential.
Data Understanding
The dataset used in this project is obtained from Kaggle and contains information about 500 customers. It includes various features such as customer name, customer email, country, gender, age, annual salary, credit card debt, net worth, and car purchase amount. The dataset provides the necessary information to train and evaluate the predictive model.
-------------------------------------------------------------------------------------------------------
Data Preparation
-----------------------------------------------------------------------------------------------------------
The data preparation phase involves several important steps, including checking for missing values, handling duplicates, removing outliers, and encoding categorical data. The steps include:

Checking for missing values and ensuring data integrity.
Removing duplicates from the dataset.
Identifying and handling outliers using Z-score-based methods.
Dropping unnecessary columns like customer name and customer email.
Scaling numerical features for consistent model performance.
Encoding categorical data, such as the country, using one-hot encoding.
-----------------------------------------------------------------------------------------------------------------------------
Exploratory Data Analysis
The exploratory data analysis (EDA) phase involves gaining insights from the data. Some key findings from EDA include:

Understanding the distribution of car purchase amounts.
Analyzing the distribution of customer ages.
Investigating the relationship between age and car purchase amounts.
Identifying top countries with high car purchase amounts.
Analyzing the influence of gender on mean car purchase amounts.
Investigating the correlation between features through correlation matrices and data distribution plots.
-------------------------------------------------------------------------------------------------------------------------------------
Modeling
The project involves training and evaluating several regression models, including:

Linear Regression
Ridge Regression
Random Forest Regression
XGBoost Regression
The models are assessed for their ability to predict car purchase amounts, and the best-performing model which is Tuned XGBoost Regression is selected for making predictions.
-----------------------------------------------------------------------------------------------------------------------------------------
Conclusion
--------------------------------------------------------------------------------------------------------------------------------
The project's key findings and conclusions are as follows:

The best-performing model for predicting car purchase amounts is the tuned XGBoost Regression model.
Insights from exploratory analysis can inform marketing strategies, such as targeting specific age groups and gender-based marketing.
The model can be deployed to make real-time predictions for new customers.
-------------------------------------------------------------------------------------------------------------------------------
Author
MOHAMMED FAIZ RAZA MULLA
razafaiz003@gmail.com
