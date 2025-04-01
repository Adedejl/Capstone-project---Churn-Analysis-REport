  ![churn image2](https://github.com/user-attachments/assets/d5f25904-0bb5-481b-a224-5399dadc7c5b)


# Capstone-project---Churn-Analysis-REport
This is the official repository for the Power BI CapStone project for the Canadian Bank.

Interact with the final dashboard here:
- [Customer churn dashboard 1](https://drive.google.com/file/d/1BujLr-nim0RcSeBX-YhnZHG4yUogBwaj/view?usp=sharing)
- [Customer churn dashboard 2](https://drive.google.com/file/d/1giP8-V8dTOBxNkYmK8gvbsTwlM479vNG/view?usp=sharing)

**[Watch Project summary](https://youtu.be/XCEgbjmS8E4)**

[View Students' Project Gallery](https://www.linkedin.com/feed/update/urn:li:activity:7087109812831891456) 

## Business problem

The Canadian bank is experiencing significant customer churn, which directly impacts revenue, profitability, and long-term customer lifetime value. However, there is a lack of clarity around the key drivers of this churn, the customer segments most at risk, and actionable strategies to retain customers. The bank needs to understand who is leaving, why they are leaving, and how to prevent it using insights from customer demographics, behavior, and engagement patterns. The business needs a data-driven approach to identify patterns, predict churn behavior, and implement effective retention strategies to reduce customer loss and enhance loyalty.

## Dataset information

The dataset used for this customer churn analysis consists of customer-level data from a Canadian bank. It includes both demographic and behavioral attributes that help identify patterns related to churn.
Key Variables in the Dataset:
- Column Name:	Description
- CustomerID:	Unique identifier for each customer
- Surname:	Customer’s last name (used for anonymized identification)
- Gender:	Gender of the customer (Male/Female)
- Age:	Customer’s age
- Geography:	Customer’s province or region (e.g., Ontario, Quebec, Alberta)
- Tenure:	Number of years the customer has been with the bank
- Balance:	Current account balance
- NumOfProducts:	Number of products the customer holds (e.g., checking, savings, credit)
- HasCrCard:	Whether the customer owns a credit card (Yes/No or 1/0)
- IsActiveMember:	Whether the customer is actively engaged (Yes/No or 1/0)
- EstimatedSalary:	Estimated annual income of the customer
- Churn:	Target variable — indicates if the customer has left the bank (Yes/No or 1/0)

## Project Objective

The objective of this project is to analyze customer churn patterns within the bank, identify key factors influencing churn, and provide data-driven insights and strategies to reduce customer attrition. By leveraging customer demographics, behavioral data, and financial indicators, the goal is to improve customer retention, increase customer lifetime value, and support strategic decision-making for the bank’s growth.

## Business Objective

Before diving into analysis, it’s critical we align with the business goals and what the users expect to see. The bank’s primary objective is to reduce customer churn by understanding why it’s happening. At the same time, business users—such as marketing and customer experience teams—need a clear and interactive dashboard that highlights churn patterns, identifies risk segments, and guides strategic action.

## Business Questions and metrics

To guide our analysis, we focused on key business questions such as: 
- What’s our churn rate?
- Who’s churning?
- Which Gender Churn the Most adn why?
- Why are they leaving?
- how can we stop it?

## Dataset Process
The dataset was cleaned by removing duplicates, correcting any inconsistencies, and ensuring the data is in a suitable format for analysis and visualization.

### Dataset before cleaning
![Churn Dataset before cleaning](https://github.com/user-attachments/assets/4f2efb72-b236-4a9b-bc74-9c90b934436e)

### Dataset after cleaning
![Chun Dataset after cleaning-customer info](https://github.com/user-attachments/assets/8134d9d6-db1f-491c-b8a5-e71af5811c23)


## Data modelling and relationships.
Dimensions with which to break down the analysis were identified. Hence, new tables for identified dimensions were created. These included:

- Churn info/Table 
- Customer info/Table
-  Order info/Table
-  Payment info/Table
 ![churn Data modelling](https://github.com/user-attachments/assets/06e57240-c283-4bda-adfa-52dadbbfbc84)

## Create visualizations and charts:
Appropriate chart types (e.g., bar charts, line charts, pie charts) were used to represent the metrics and insights. Interactive features such as filters, drill-down options, and tooltips were used for detailed information.
![churn Data Visualization1](https://github.com/user-attachments/assets/28f8e6db-921f-41ac-81cd-ed42560e687a)



## Dashboard Testing and Refinement
To guide each student throughout the project, they get the opportunity to schedule a one-on-one session with an instructor. This is to get feedback on their work done and to see if they were meeting up with the project's requirements. The students gathered feedback from these sessions and made necessary adjustments to their dashboard layout, visualizations, and insights based on the feedback received.

## Insights
- Females have a higher churn rate.
- Customers without a credit card churn more than those who have one.
- Inactive members churn at a much higher rate than active members.
- Churn is highest among younger customers (e.g., 18–30 years old).
- Some regions have higher churn than others—this could be due to competition, service issues, or regional preferences.
- Customers with low balances churn more often.
- New customers churn the most, especially in the first 1–2 years.
- 

## Recommendation
- Many new customers leave early, especially the female gender. The bank should welcome them better, maybe send helpful messages, explain products clearly and follow up in the first few months.
- Customers with only one product are more likely to leave. The bank should offer deals or bundles so people use more services like credit cards, savings or insurance.
- Customers with low account balances are more likely to churn. The bank can offer low-fee accounts, small rewards, or financial tips to keep them interested.
- Since churn rates are a bit different by gender, the bank can try different messages or offers for men and women based on their needs.
- We can mix data like gender, tenure, and balance to find high-risk groups. For example: ‘New female customers with low balance’—and help them before they leave



## Deployment and Documentation
Once the dashboard was finalized, it was deployed to Power BI service. The project process and deliverables are documented here on GitHub.

Interact with all files [here](https://drive.google.com/drive/folders/1-OBRSZi56hVZvPPsehdbZAbsOcwzutqp?usp=drive_link) 
