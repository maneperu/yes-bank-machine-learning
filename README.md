# Yes Bank Cost Prediction Analysis
**Overview:**
Welcome to the Yes Bank Stock Closing Price Prediction project repository! This project aims to predict the closing price of Yes Bank stock, considering the impact of the 2018 fraud case involving Rana Kapoor. We have developed machine learning models, including Ridge Regression, Random Forest, and XGBoost Regressor, to achieve this objective.


**Problem Statement:**
Yes Bank, a prominent bank in India, has been in the spotlight due to the fraud case involving Rana Kapoor. The objective of this project is to analyze the impact of this case on the bank's stock prices and develop predictive models to forecast the closing price of the stock. The dataset includes monthly stock prices since the bank's inception, providing essential features such as closing, opening, highest, and lowest stock prices of each month.

**Business Objective:**
The primary business objective is to leverage regression models to provide accurate predictions of Yes Bank's stock closing price. These predictions will aid stakeholders in making well-informed investment decisions, managing risks effectively, optimizing portfolios, and establishing early warning systems to alert potential fraud cases similar to that involving Rana Kapoor.

**Steps Involved:**
1.Data Preprocessing: Cleaned and transformed the dataset.
2.Exploratory Data Analysis: Examined the influence of the fraud case on stock prices.
3.Feature Engineering: Engineered additional features to capture temporal patterns.
4.Model Building: Utilized regression models including Linear Regression, Ridge Regression, Random Forest Regressor, and XGBoost Regressor.
5.Evaluation: Evaluated model performance using R2 score and selected the best-performing model.

**Key Insights:**
1.XGBoost Regressor performed the best with an R2 score of 0.97 on both train and test datasets, making it suitable for predicting the closing price.
2.Visualization of the target variable indicates a significant decline in stock prices during the period of the 2018 fraud case.
3.Log transformation was applied to address positively skewed distributions of variables.
4.Additional features were engineered, including lag features, to capture temporal trends and patterns, thereby considering the impact of the fraud case.
