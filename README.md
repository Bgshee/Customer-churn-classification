# Customer-churn-classification
## Project Overview
This project focuses on predicting customer churn for SyriaTel, a telecommunications company.This will help to identify at-risk customers and improve retention strategies. 
The company is interested in reducing how much money is lost because of customers who don't stick around very long. By looking at various factors like total day calls, total eve calls, customer service calls, churn etc I will guide the company on how to reduce the churn rate so as to reduce loss.The primary goal is to build a machine learning model to classify whether a customer is likely to churn

## Project Objectives
1.To develop machine learning models to be able to predict customer churn with high accuracy.
2.Use performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to evaluate and improve the model's predictive power.
3.To identify the key factors driving customer churn in the company.
4.To provide actionable recommendations based on data-driven insights to enhance customer retention efforts.

## Data Analysis
This analysis uses data sourced from  SyriaTel, a telecommunications company a CSV file. It provides comprehensive information on total day calls, total eve calls, customer service calls, total night calls, churn, total intl calls among other key performance factors to help the company make informed decisions. 
-Data Visualizations
(a)Barchart to check the count of churn
-This is to check the distribution of churn rates for the telecommunication company.
![Capture](https://github.com/user-attachments/assets/30b3f7f5-fcb4-49f6-b9b5-1a20971809f2)

(b)Correlation heatmaps
-This is to show the correlation and relation between the different features
(c)Barchart to check the count of churn and international plan
-Correlation between international plan and churn: Customers with an international plan churned more frequently.
(d)Plotting distributions of the: 'total day minutes',  'customer service calls', 'total night minutes', 'total intl minutes' in relation to churn rate.
-To see how these features are related with churn

## Modelling
-The Models I chose to use are:
(a)Baseline Model: Logistic Regression.
(b)2nd Model: Decision Trees with hyperparameter tuning
(c)3rd Model: Random Forest with hyperparameter tuning 

-Each model and its performance
1.Logistic Regression
-Accuracy: 0.7691154422788605
-ROC-AUC: 0.8270475457439738
-Precision: True:0.37  False:0.95
-Recall: True:0.77  False:0.77

2.Decision trees with hyperparameter tuning
-Accuracy: 0.9175412293853074

-ROC-AUC:0.8889637196935241
-Precision: True:0.83  False:0.93
-Recall: True:0.57  False:0.98


3.Random Forest with hyperparameter tuning
-Accuracy:0.9265367316341829
-ROC-AUC: 0.9118007207081132
-Precision: True:0.79  False:0.95
-Recall: True:0.70  False:0.97

-The model that performed best is Random Forest with hyperparameter tuning and this is because of its balance of precision, recall, overall accuracy and ROC-AUC . Which shows the model is highly effective at distinguishing between churners and non-churners across all classification thresholds, which is critical for customer retention strategies

## Conclusion
1.Random Forest models outperforms both Logistic Regression  and Decision Trees in capturing complex patterns in the data and better modeling of the data.
2.The high accuracy and recall values of the Random Forest with hyperparameter tuning model demonstrates its reliability in predicting customer churn.
3.That Customers with international plans and high total charges are at higher risk of churn.


