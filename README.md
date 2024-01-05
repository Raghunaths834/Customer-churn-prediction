**CUSTOMER CHURN PREDICTION**

**Overview**:   

   Customer churn prediction is crucial for businesses as it helps forecast which clients might cancel their service based on their usage patterns. Retaining existing customers is more cost-effective than 
   acquiring new ones. By identifying at-risk customers and taking personalized marketing actions, businesses can maximize retention. Churn prediction addresses a widespread issue across sectors. Losing a 
   client means losing a significant investment in acquisition, requiring time and effort for replacement. Predicting potential churn and offering incentives to retain customers can lead to substantial cost 
   savings for a business.

**Objectives**:
         
   Understanding the data features driving customer churn is pivotal. This analysis will uncover patterns or behaviors indicating potential churn, enabling proactive retention strategies.
   Finding the most suited machine learning model for correct classification of Churn and non-churn customers.

**Dataset**:
  [ kaggle-- Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

*_The dataset encompasses the following details_*:

*Churn Column*-- Indicates customers who terminated services within the last month.

*Services Subscribed*-- Includes phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.

*Customer Account Details*-- Encompasses tenure as a customer, contract type, payment method, preference for paperless billing, monthly charges, and total charges incurred.

*Demographic Information*-- Provides insights into customers' gender, age range, as well as their marital status, indicating if they have partners and dependents.

**Requirements**:

Python 3.x

Libraries: (e.g., scikit-learn,Matplotlib, pandas, seaborn, and NumPy,Imblearn)

**Challenges Overcome**:

   Handled imbalanced dataset by implementing various resampling techniques (e.g., oversampling minority class, undersampling majority class, SMOTE) to mitigate class imbalance.
 
 **Approach**:
 
   Conducted comprehensive analysis and feature engineering to identify key predictors of churn.
   Employed various classification models (e.g., Random Forest, Logistic Regression, Gradient Boosting) to train and evaluate the predictive performance.
   Utilized techniques such as cross-validation and hyperparameter tuning to optimize model performance.

**Result**:

   Achieved an F1 score of 88% for predicting customers likely to churn ('Churn == Yes') and 90% for those not likely to churn ('Churn == No'), demonstrating robust performance across both classes.


![Screenshot (133)](https://github.com/sahooraghunath/Customer-churn-predictionn/assets/119792506/0841db70-190d-449c-a15e-3aa21fd0687e)

![Screenshot (132)](https://github.com/sahooraghunath/Customer-churn-predictionn/assets/119792506/f7de5745-2a70-41ab-95a4-a8736a6ac5b2)
          
