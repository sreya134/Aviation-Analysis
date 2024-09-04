**Predictive Modeling of Airport Efficiency and Delays**

This project applies various machine learning techniques to predict and analyze operational efficiency and taxi-in delays at Newark Liberty International Airport (EWR). The study aims to provide insights that can enhance airport operations, reduce delays, and improve passenger satisfaction.

Table of Contents
Introduction
Data
Methodology
Models
Results
Conclusion
Technologies Used
References
Introduction
**Newark Liberty International Airport** (EWR) is a major transportation hub, facing significant operational challenges due to high passenger and flight volumes. This project focuses on predicting taxi-in delays using data from 2018 and 2023, incorporating factors such as time of day, weather conditions, and airport congestion.

Data
The datasets used in this project were obtained from EWR's operational records and include various metrics such as efficiency computations, delay averages, and facility reports. Data preprocessing involved cleaning, normalization, and feature engineering to ensure accurate and reliable analysis.

**Methodology**
Data Preprocessing: Handling missing values, removing duplicates, filtering irrelevant data, and converting data types.
Feature Engineering: Creating new temporal variables and interaction terms to better understand the dynamics affecting taxi-in times.
Exploratory Data Analysis: Visualizing trends and correlations between variables to identify patterns in taxi-in delays.
Models

**STATS models**
STATS models is a library that is specifically created for the purpose of statistical modeling and analysis. The software provides powerful capabilities for estimating diverse statistical models, executing statistical tests, and enabling comprehensive data exploration. This library is highly beneficial for regression analysis, one of its most common uses. It gives detailed statistical data, making it appropriate for traditional statistical analysis and modeling.

The following machine learning models were implemented and compared:

Linear Regression: A baseline model to understand linear relationships.
Lasso Regression: Used for feature selection and to prevent overfitting by shrinking less important coefficients to zero.
Ridge Regression: Addressed multicollinearity by penalizing large coefficients.
Random Forest: An ensemble method that captures complex non-linear interactions and provides feature importance scores.
XGBoost: A gradient boosting technique that optimizes model complexity and accuracy.
Results
Evaluated model performance using metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).
Random Forest and XGBoost demonstrated superior predictive accuracy, making them suitable for real-time applications in airport operations.
Identified significant factors affecting taxi-in delays, including time of day, weather conditions, and airport congestion.
Conclusion
The project highlights the importance of advanced predictive models in improving airport operational efficiency. The insights gained from this study can guide strategic planning and resource allocation, ultimately enhancing passenger experience.

![image](https://github.com/user-attachments/assets/9d86aafc-9758-4b72-9d1d-c1ced50118bb)

**Technologies Used**
Programming Languages: Python
Libraries: Pandas, Scikit-learn, XGBoost
Tools: Data Preprocessing, Feature Engineering, Machine Learning, Data Visualization
**References**
Diana, T. (2018). Can machines learn how to forecast tax-out time?
Anupkumar, A. (2023). Economic impact of flight delays
Choi, S., & Kim, Y. J. (2021). Airport capacity prediction
Dinler, N., & Rankin, W. B. (2020). On-time arrival performance

