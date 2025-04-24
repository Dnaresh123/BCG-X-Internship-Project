# PowerCo Customer Churn Prediction
## Project Overview
This project aims to predict customer churn for PowerCo, an energy company, using historical customer and pricing data. By analyzing customer usage patterns, pricing data, and other relevant features, we can predict the likelihood of a customer churning, which will help PowerCo to take proactive measures to retain high-risk customers.

## Objective
Predict customer churn: Using machine learning techniques, we aim to predict whether a customer will churn based on various features.

Feature engineering: We explored and created new features such as differences in pricing, customer usage patterns, and churn indicators.

Predictive modeling: We used Random Forest Classifier to build a model for predicting churn.

## Data Sources
The following datasets were used for this analysis:

Historical Customer Data: Contains information on customer usage, sign-up dates, forecasted usage, etc.

Historical Pricing Data: Contains variable and fixed pricing information.

Churn Indicator Data: Indicates whether a customer has churned or not.

## Tools and Libraries Used
Python: The primary language used for data processing and machine learning.

Pandas: Used for data manipulation and cleaning.

Scikit-learn: Used for building machine learning models.

Matplotlib and Seaborn: Used for data visualization.

Jupyter Notebook: Used for creating an interactive environment for coding, analysis, and visualizations.

## Approach
Exploratory Data Analysis (EDA): We started by understanding the structure and distributions of the data. This included checking for missing values, data types, and performing basic statistical analysis.

Feature Engineering: We engineered new features by analyzing price sensitivity, customer behavior, and other relevant columns.

Predictive Modeling: We applied a Random Forest Classifier to predict customer churn based on the engineered features.

Model Evaluation: We used metrics such as accuracy, precision, recall, and F1 score to evaluate the performance of the model.

## Model Evaluation Metrics
Accuracy: The percentage of correct predictions made by the model.

Precision: The percentage of true positive predictions among all positive predictions.

Recall: The percentage of true positive predictions among all actual positive instances.

F1-Score: The harmonic mean of precision and recall.

## Results
The Random Forest classifier achieved a strong performance with an accuracy of 78% on the test data. Key features contributing to churn prediction included price differences between December and January, customer usage trends, and contract tenure. These findings provide actionable insights for PowerCo to enhance customer retention strategies by focusing on customers most likely to churn.

The model can be used to predict which customers are at risk of churning, allowing PowerCo to focus on retaining them.


## Conclusion
This project demonstrates how feature engineering and machine learning can be used to predict customer churn for an energy company. The insights gained can help PowerCo to prioritize high-risk customers and implement retention strategies effectively.
