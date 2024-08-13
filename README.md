# Telecom-Customer-Churn-Prediction
Project Overview
This data science project focuses on developing a machine learning model to predict customer churn for a telecommunications company. The goal is to identify factors contributing to customer churn and build a predictive model to help the company proactively retain customers.
Dataset
The analysis was performed on a telecom customer dataset, which includes 7,043 customers and 21 features such as customer demographics, services used, contract information, and billing details.
Key Steps
1. Data Preprocessing and Feature Engineering

Handled missing values in the 'TotalCharges' column
Created new features: 'TotalServices', 'AvgMonthlyCharges'
Encoded categorical variables

2. Exploratory Data Analysis (EDA)

Analyzed churn rate across different customer segments
Visualized the relationship between key variables and churn
Created correlation heatmap to identify relationships between features

3. Model Building

Used Random Forest Classifier
Split the data into 80% training and 20% testing sets
Trained the model on 5,634 samples

4. Model Evaluation

Achieved 82% accuracy on the test set
Generated classification report and confusion matrix
Analyzed feature importance

Key Findings

The model achieved an accuracy of 82% in predicting customer churn.
Contract type was identified as the most significant factor influencing churn.
Customers with month-to-month contracts are 3 times more likely to churn than those with long-term contracts.
Higher monthly charges and shorter tenure are also strong indicators of potential churn.
Fiber optic internet service users showed a higher tendency to churn compared to DSL users.

Technologies Used

Python
Pandas for data manipulation
Scikit-learn for machine learning
Matplotlib and Seaborn for data visualization

Future Work

Implement hyperparameter tuning to improve model performance
Explore other algorithms such as XGBoost or neural networks
Develop customer segmentation analysis for targeted retention strategies

How to Run

Clone this repository
Install the required packages: pip install -r requirements.txt
Run the Jupyter notebook: jupyter notebook Churn_Prediction_Analysis.ipynb

Author
Arun kumar chukkala
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
