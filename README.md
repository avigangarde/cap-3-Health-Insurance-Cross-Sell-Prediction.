# Cap-III-Health-Insurance-Cross-Sell-Prediction

This is the second project in the category of supervised machine learning, in the  type of classification. "Health insurance cross sell prediction" is the project name. By predicting whether or not a customer will be interested in purchasing insurance, we will assist the insurance firm. Insurance companies hold all the information about their clients who have health insurance. The business is now attempting to cross-sell customers vehicle insurance. So, we need to identify the client who will purchase vehicle insurance from the specified insurance provider.

Let's break this down a little more in terms of a business context. Our client is an insurance company that has previously offered health insurance to its clients. Now, they need our assistance in developing a model to determine whether the policyholders' clients from the prior year will also be interested in the company's provision of vehicle insurance. A policy of insurance is an agreement whereby a business agrees to guarantee reimbursement for a specific loss, damage, disease, or death in exchange for the payment of a specific premium.

Vehicle insurance works similarly to medical insurance in that customers must pay an annual premium to the insurance provider firm in order for them to be compensated (referred to as Sum assured) in the event that their car is involved in an unfortunate accident.

Using a model to determine whether a consumer would be interested in vehicle insurance is very beneficial for the business since it allows it to plan its marketing strategy to reach out to those customers and maximise its business model and revenue.

So, we have information on demographics (gender, age, region code type), vehicles (car age, damage), policies (premium, sourcing channel), etc. to determine whether a customer would be interested in purchasing vehicle insurance.

So first we  do data preprocessing and then  feature selection and then we  build some kind of classification model. and try to compare different evaluation metrics and find out which model performs well.
# Dataset information :

1. id :	Unique ID for the customer

2. Gender	: Gender of the customer

3. Age :	Age of the customer

4. Driving_License	0 : Customer does not have DL, 1 : Customer already has DL

5. Region_Code :	Unique code for the region of the customer

6. Previously_Insured	: 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

7. Vehicle_Age :	Age of the Vehicle

8. Vehicle_Damage	 :1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

9. Annual_Premium	: The amount customer needs to pay as premium in the year

10. PolicySalesChannel :	Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

11. Vintage :	Number of Days, Customer has been associated with the company

12. Response :	1 : Customer is interested, 0 : Customer is not interested

# conclusion from the project:

The ML model for the problem statement was created using python with the help of the dataset, and the ML model created with Random Forest and XGBClassifier models performed better than Logistics Regression model. Thus, for the given problem, the models created by XGBClassifier is preferred.

1] Customers of age between 30 to 60 are more likely to buy insurance.

2] Customers with Driving License have higher chance of buying Insurance.

3] Customers with Vehicle_Damage are likely to buy insurance.

4] The variable such as Previously_insured , Vehcile_Damage are more affecting the target variable.

5] The variable such as Driving_License , Gender are not affecting the target variable.
