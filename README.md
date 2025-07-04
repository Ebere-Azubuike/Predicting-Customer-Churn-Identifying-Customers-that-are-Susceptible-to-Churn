# Predicting-Customer-Churn-Identifying-Customers-that-are-Susceptible-to-Churn
# Project Objectives
The primary objective of this project is to develop a predictive model that can accurately forecast customer churn within the telecommunications industry. Specifically, the project aims to leverage historical customer data and relevant features to create a machine learning model capable of identifying customers who are likely to churn. The model's performance will be assessed using appropriate evaluation metrics. It includes data collection, Exploratory data analysis (EDA), feature engineering, model training, evaluation and documentation.

**The objectives of this project are as follows:**

Develop a predictive model to identify customers at risk of churning.

Analyze the key factors contributing to customer churn.

# Business Problem
Reder Telecom is facing an increasing rate of customer churn, which is the percentage of customers who switch to competitors' services or terminate their subscriptions. The telecommunications industry is highly competitive, with multiple players offering similar services, and retaining existing customers is becoming increasingly difficult. 

**The specific obstacles the company faces include:** 
Intense competition from the many competitors in the market.
Changing customer Preferences usually because of their need for personalized and high-quality services.
Pricing pressures from competitors has affected profitability making competitive pricing very difficult to sustain.
Network quality and performance issues that influence customer satisfaction, which leads to dissatisfaction and churning.
Difficulty in building  and maintaining customer loyalty.
# Why Churn Prediction
<img width="143" alt="image" src="https://github.com/user-attachments/assets/3c20c443-3885-4891-b653-70ad0bd83997" />


Churn prediction is a strategy that uses customer data to identify clients who are least likely to renew their contracts. The significance of initiating this project lies in its potential to address the aforementioned challenges and enhance Reder Telecom's operations. Here are the top reasons that underline the importance of this project:

**Cost Reduction:** Acquiring new customers is more expensive than retaining existing ones. Reducing churn can lead to substantial cost savings.

**Revenue Growth:** A reduction in churn can result in increased revenue as existing customers stay longer and potentially buy additional services.

**Customer Satisfaction:** Understanding customer behavior and preferences enables Reder Telecom to improve its services, leading to higher customer satisfaction and loyalty.

**Competitive Advantage:** By leveraging data analytics to predict churn, Reder Telecom can proactively retain customers and gain a competitive advantage over rivals.

**Data-Driven Decision-Making**: In an industry where data is abundant, using analytics to drive decisions can lead to more informed and effective strategies.

# Dataset Description
The dataset available from the company contains the following information:

Customer ID: A unique identifier for each customer.

Name: The name of the customer.

Age: The age of the customer.

Gender: The gender of the customer.

Location: The location or city where the customer is based.

Email: The email address of the customer.

Phone: The phone number of the customer.

Address: The postal address of the customer.

Segment: The customer segment or category to which the customer belongs (e.g., Segment A, Segment B, Segment C).

Service Interactions: A list of dictionaries representing the customer's interactions with customer service. Each dictionary includes the type of interaction (e.g., Call, Email, Chat) and the date of the interaction.

Type: Type of service, it could be Call, Email or Chat.

Date: Date of the service interaction.

Payment History: A list of dictionaries representing the customer's payment history. Each dictionary includes the payment method (e.g., Credit Card, PayPal) and the number of late payments.

Method: Payment method, can either be Credit Card, PayPal or Bank Transfer.

Late Payments: Number of late payments.

Engagement Metrics: A dictionary containing engagement metrics, such as the number of logins and the frequency of engagement (e.g., Daily, Weekly, Monthly).

Logins: The number of logins the user made.

Frequency: How often a customer logs in to the platform. Could be Daily, Weekly or Monthly.

Feedback: Feedback provided by the customer, including a rating (e.g., 1 to 5) and a comment.

Rating: A value between 1 and 5 that indicates the customer’s feedback rating.

Comment: The comment left by the customer for the feedback.

Marketing Communication: A list of dictionaries representing the customer's history of marketing communication, including dates when emails were sent, opened, and clicked.

Email Sent: Date when email was sent.

Email Opened: Date when email was opened.

Email Clicked: Date when email was clicked.

NPS: The Net Promoter Score (NPS) of the customer, which measures customer loyalty and satisfaction on a scale of 0 to 10.

Churn Label: A binary label indicating whether the customer has churned (1 for churn, 0 for no churn).

Timestamp: The timestamp indicating when the data was recorded for the customer.



# Data Preprocessing and Feature Engineering

1. Created new features that may have predictive power
2. Converted categorical variables to numerical variables, using encoding techniques e.g mail = 1, sms =2, because ML works with numbers
3. Scaled or normalized variables if necessary
4. Splitted the data into training and testing subsets
5. Removed irrelevant features

# Machine Learning Models
1. Logistic Regression
2. Decision Tree
# Metrics for evaluation includes
1. Accuracy Score
2. Precision Score
3. Recall Score
4. F1 Score

**For modelling using Logistic Regression and Decision Tree, the following outcomes were gotten**
# A. Evaluation Using Train and and validation evaluation on dataset.
For Accuracy score: the Decision Tree model performed slightly better

For Precision score: the Decision Tree model performed slightly better

For Recall score: the Logistic Regression model performed slightly better

For F1 score: the Decision Tree model performed slightly better.

# B. Evaluation the Test score 
For Accuracy score: the Decision Tree model performed slightly better

For Precision score: the Decision Tree model performed slightly better

For Recall score: the Decision Tree model performed slightly better

For F1 score: the Decision Tree model performed slightly better


