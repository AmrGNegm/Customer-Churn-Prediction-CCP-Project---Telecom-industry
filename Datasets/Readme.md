Telco Customer Churn
Focused customer retention programs

https://www.kaggle.com/blastchar/telco-customer-churn

About this file
Telcom Customer Churn
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.
The raw data contains 7043 rows (customers) and 21 columns (features).
The “Churn” column is our target.

# features (20 columns)

## Demographic info about customers =>
### customerID : Customer ID.
DataType: string  - Example: 5575-GNVDE , 3668-QPYBK , 7892-POOKP.
### gender : Whether the customer is a male or a female.
### SeniorCitizen : Whether the customer is a senior citizen or not (1, 0).
### Partner : Whether the customer has a partner or not (Yes, No).
### Dependents : Whether the customer has dependents or not (Yes, No).
### tenure : Number of months the customer has stayed with the company.

## Services that each customer has signed up for =>
### PhoneService : Whether the customer has a phone service or not (Yes, No).
### MultipleLines : Whether the customer has multiple lines or not (Yes, No, No phone service).
### InternetService : Customer’s internet service provider (DSL, Fiber optic, No).
### OnlineSecurity : Whether the customer has online security or not (Yes, No, No internet service).
### OnlineBackup : Whether the customer has online backup or not (Yes, No, No internet service).
### DeviceProtection : Whether the customer has device protection or not (Yes, No, No internet service).
### TechSupport : Whether the customer has tech support or not (Yes, No, No internet service).
### StreamingTV	:	Whether the customer has streaming TV or not (Yes, No, No internet service).
### StreamingMovies : Whether the customer has streaming movies or not (Yes, No, No internet service).

## Customer account information =>
### Contract : The contract term of the customer (Month-to-month, One year, Two year).
### PaperlessBilling : Whether the customer has paperless billing or not (Yes, No).
### PaymentMethod : The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
### MonthlyCharges : The amount charged to the customer monthly.
### TotalCharges : The total amount charged to the customer.


# and Our Target:
## Churn : Customers who left within the last month - Whether the customer churned or not (Yes or No)


Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]
Inspiration
To explore this type of models and learn more about the subject.

New version from IBM:
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113
