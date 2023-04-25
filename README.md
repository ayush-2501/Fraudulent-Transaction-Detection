# Fraudulent-Transaction-Detection
Reasons to use Random Forest & Decision Tree

We have seen that, while Random Forest has greater precision, accuracy for both it and Decision Tree is equal. Precision is crucial in a fraud detection model because, instead of correctly predicting legitimate transactions, we want to predict fraudulent ones while ignoring legitimate ones. If either of the two conditions is not met, we risk catching the innocent person while ignoring the offender.
The highly unbalanced dataset is main factor in my decision to use this model (Legit: Fraud :: 99.87:0.13). Random forest creates multiple decision trees, which helps the model understand the data more simply (though it takes time) because decision trees make decisions in a boolean manner.
Models like XGBoost, Bagging, ANN, and Logistic Regression may give good accuracy but they won't give good precision and recall values.

What are the key factors that predict fraudulent customer?

Is the request's source secured or not?
Is the name of the organisation soliciting donations legitimate or not?
A vendor's past transactions.
What kind of prevention should be adopted while company update its infrastructure?

Only use intelligent vertified apps.
Explore websites with encryption.
Utilize encrypted internet connections(VPN).
Maintain the security on your laptop and mobile device.
Don't reply to unauthorised calls, SMS messages, or emails.
Get in touch with your bank right away if you believe your security has been compromised or you have been duped.
Assuming these actions have been implemented, how would you determine if they work?

Bank sending E-statements.
Customers keeping a check of their account activity.
Always keep a log of your payments.
