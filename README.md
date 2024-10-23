# Customer-Churn-Prediction

<h3>The IBM Customer churn dataset includes information about:</h3>
* Customers who left within the last month – the column is called Churn

* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.

* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.

* Demographic info about customers – gender, age range, and if they have partners and dependents

<h3>Customer Churn Prediction is a machine learning project aimed at predicting whether a customer is likely to stop using a service based on their usage patterns, demographic data, and interaction with the company. By identifying customers who are at risk of leaving, businesses can proactively engage with them to improve retention and reduce churn rates.</h3>

<h4>For this model We are going to use below features from IBM Customer Churn Dataset:</h4>

categorical_columns = ['gender', 'Partner', 'Dependents', 'PhoneService', 'MultipleLines',
                       'InternetService', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection',
                       'TechSupport', 'StreamingTV', 'StreamingMovies', 'Contract',
                       'PaperlessBilling', 'PaymentMethod']

numerical_columns = ['SeniorCitizen', 'tenure', 'MonthlyCharges', 'TotalCharges']

\* The Column named 'Churn' will be our target. The indicates whether a customer has stopped using the service, with values of "Yes" for customers who churned and "No" for those who did not.
