# PWC---Customer-Retention-Analysis
## Content
- [Problem Statement](#problem-statement)
- [Data Description](#data-description)
- [Insights](#insights)
## Problem Statement
Problem: Manager needs to understand the customer information and find out the reason they terminate the contract. The analysis is focused on getting insights of churning customer, and recognize remaining customers who are at risk. 
Objectives: The purpose of this analysis is to create a Customer Retention Dashboard in Power BI for the Customer Retention Manager that reflects all relevant Key Performance Indicators (KPIs) and metrics to:
- Self-exploratory the customer demographics and insights (churning & retaining).
- Actively approach who is at risk with the risk level of specific customer
- Contain many metrics and plots related to a single area of business for discussing with higher managers and generating further analysis.
- Allows for minimal interaction.
- Based on finding recommend improving customer retention.
## Data Description
|Field Name|Description|Data Type|
|----------|-----------|----------|
|customerID|Represents the unique number of the customer in the dataset|Text|
|gender|Describes the gender of the customer|Text|
|SeniorCitizen|Describes if the customer is a senior citizen|Text|
|Partner|	Describes if the customer has a partner|Text|
|Dependents|	Describes if the customer has a dependent|Text|
|tenure|	Describes how long as a customer	|number|
|PhoneService|	Describes if the customer has registered a phone service|Text|
|MultipleLines|	Describes if the customer has registered multiple lines	|Text|
|InternetService|	Describes if the customer has registered for Internet service	|Text|
|OnlineSecurity|	Describes if the customer has registered for online security	|Text|
|OnlineBackup|	Describes if the customer has registered for online backup	|Text|
|DeviceProtection|	Describes if the customer has registered for device protection	|Text|
|TechSupport|	Describes if the customer has registered for tech support	|Text|
|StreamingTV|	Describes if the customer has registered to stream tv	|Text|
|StreamingMovies|	Describes if the customer has registered to stream movies	|Text|
|Contract|	Describes the length of the contract of the customer	|Text|
|PaperlessBilling|	Describes if the customer has registered for paperless billing	|Text|
|PaymentMethod|	Describes the payment method of the customer	|Text|
|MonthlyCharges|	Represents the monthly charge incurred by the customer	|Decimal number|
|TotalCharges|	Represents the total charge incurred by the customer	|Decimal number|
|numAdminTickets|	Represents the number of admin tickets opened by the customer	|Whole number|
|numTechTickets|	Represents the number of tech tickets opened by the customer	|Whole number|
|Churn|	Describes if the customer is at risk of churn	|Text|
## Insights
Based on the analysis and data visualization, several key insights can be drawn:
### Customer Contract Preferences:
- Customers on longer contracts, especially the Two-Year contract, tend to stay with the company for a longer duration, indicating a higher level of loyalty. In contrast, Month-to-Month contract customers are at a higher risk of churn, with 7043 customers potentially at risk, and a churn rate of 27%.
- Customers on Month-to-Month contracts are generally new to the company, making them more vulnerable to leaving, especially as they are less committed to longer-term plans.
### Impact of Service and Security:
- A significant portion of churned customers did not sign up for additional services like Online Security, Tech Support, or Phone Services, which suggests that these offerings may play a key role in customer retention.
- Issues with Fiber Optic services were a contributing factor, with 42% of churned customers using this service, highlighting a potential area for improvement.
###  Customer Demographics:
- Senior citizens (16% of the customer base) have a much higher churn rate compared to younger customers, almost double the rate of younger customers, which might indicate dissatisfaction or different service needs among this group.
### Pricing Sensitivity:
- Customers with higher monthly charges are more likely to stay with the company, while those with lower total charges are at a higher risk of churn, suggesting that pricing strategies could impact retention.
In conclusion, focusing on improving services for customers on Month-to-Month contracts, offering bundled security services, addressing issues with Fiber Optic services, and tailoring offers for senior customers could help in reducing churn and improving customer retention.
