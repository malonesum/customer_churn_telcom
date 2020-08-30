# Telco Customers and Predicting Churn
Churn analysis via Logistic Regression, Random Forest, Recursive Feature Elimination (Logisitic Regression).

This analysis and presentation was my final project in my Data Science certification program at UCLA

 The goal of the project was to utilize all the skills I have learned throughout the Machine Learning course to:
	
	-- 	Identify a business problem
	
	-- 	Explore the data
	
	-- 	Choose models for prediction
	
	-- 	Report results and recommendations to the company
	
	
# Methodology
1. Cleaning the Data
2. Exploratory Data Analysis
3. Machine Learning Models: LR, RF, RFE
4. Model Performance: Confusion Matrix, Classification Report
5. Conclusion and Recommendations


# Some of the features that best correlate with churn include:
	Month-to-month contracts - Figure 5
	Fiber Optic Service and DSL internet services - Figure 6
	Electronic Check payment method - Figure 7
	Paperless Billing - Figures 8 - 9
	Customers not enrolled in additional services - Figure 10
	Tenure - Figure 11


# Model Performance via Classification Report, Confusion Matrix
Surprisingly, the Logistic Regression model performed the best out of the three models (F1 score .64 and recall .77). The worst model implemented was the Random Forest with an F1 score of .37, which is not surprising considering the dataset contains 49 features. RFE performed relatively poorly as well, resulting in a F1 score of .52.


# Utilized and edited code from various sources:
// https://www.kaggle.com/blastchar/telco-customer-churn
// https://github.com/irinhwng/Consumer-Insights-Metrics_and_Predictions
// https://github.com/akshayr89/Telecom_Churn_Model
// https://scikit-learn.org/
