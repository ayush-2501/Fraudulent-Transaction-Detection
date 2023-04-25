# Fraudulent-Transaction-Detection

## Business Context
This case needs us to create a model for anticipating fraudulent transactions for a financial business and then utilize the model's insights to create an actionable strategy. The case data is provided in CSV format, including 6362620 rows and 10 columns.

The model would be estimated on the calibration data and evaluated on the validation data using standard model development processes. This situation necessitates both statistical analysis and creative/judgmental thinking. 


## Conclusion
Reasons to use Random Forest & Decision Tree

1. We have seen that, while Random Forest has greater precision, accuracy for both it and Decision Tree is equal. Precision is crucial in a fraud detection model because, instead of correctly predicting legitimate transactions, we want to predict fraudulent ones while ignoring legitimate ones. If either of the two conditions is not met, we risk catching the innocent person while ignoring the offender.
2. The highly unbalanced dataset is main factor in my decision to use this model (Legit: Fraud :: 99.87:0.13). Random forest creates multiple decision trees, which helps the model understand the data more simply (though it takes time) because decision trees make decisions in a boolean manner.

Models like XGBoost, Bagging, ANN, and Logistic Regression may give good accuracy but they won't give good precision and recall values.

What are the key factors that predict fraudulent customer?

1. Is the request's source secured or not?
2. Is the name of the organisation soliciting donations legitimate or not?
3. A vendor's past transactions.

What kind of prevention should be adopted while company update its infrastructure?

1. Only use intelligent vertified apps.
2. Explore websites with encryption.
3. Utilize encrypted internet connections(VPN).
4. Maintain the security on your laptop and mobile device.
5. Don't reply to unauthorised calls, SMS messages, or emails.
6. Get in touch with your bank right away if you believe your security has been compromised or you have been duped.

Assuming these actions have been implemented, how would you determine if they work?

1. Bank sending E-statements.
2. Customers keeping a check of their account activity.
3. Always keep a log of your payments.
