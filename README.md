# Telco-Churn-Analysis
This project provides an in-depth analysis of customer churn in the telecommunications industry using Python

## Project Overview:
The goal of this analysis is to:

- Analyze customer churn data to understand key factors associated with churn.
- Visualize churn rates by demographic and account features.
- Provide insights and recommendations to reduce churn.

## About the Dataset
The dataset used is kaggle publicly available and contains differnent information about customers:
[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

-  `Demographics`:
 Gender, senior citizen status, partner status, and dependents.
-  `Account Information`:
  Contract type, payment method, and monthly charges.
-  `Services`:
 Internet service, online security, device protection, and more..

## Cleaning
- Our dataset consisted of a total of 7043 rows and 21 columns .
- It is found almoust in a clean form .
- It looks a bit tidy with no NaNs no duplicated values.
- TotalCharges column has null values that need to be handled, it has 11 nulls, and we replaced them by zero After finding that tenure values equal to zero
- No columns needed to be dropped.

## KPIs
The KPI dashboard provides a high-level summary of critical metrics:

- Total Customers: 7,043
- Churned Customers: 1,869
- Current Customers: 5,174
- Churn Rate: 26.5%
- Average of Monthly Charges: 64.76
- Annual Revenue: $5.47M

## Strategic Insights

`Churn Drivers`:
- High monthly charges and short tenure increase churn risk.
- Month-to-month contracts and electronic check payments correlate with higher churn.
  
`Opportunities`:
- Encourage longer-term contracts with discounts or incentives.
- Improve retention among senior citizens with targeted offers.
  
`Challenges`:
- Fiber optic customers show higher churn, indicating possible service quality concerns.
- Lack of add-on services (Tech Support, Online Security) increases churn risk.

## Conclusion

These are derived conclusions after completing our data visualisation phase.

- `Churn Rate`: The company has a churn rate of 26.5%, with 1,869 out of 7,043 customers at risk. The total annual revenue stands at $5.47M.
- `High Churn Among Month-to-Month Contracts`: Customers on a month-to-month contract have a higher churn rate compared to those with longer-term contracts, indicating that month-to-month customers may have less loyalty.
- `Dependents and Stability`: customers without partners or dependents have higher churn rates, highlighting a potential need for targeted retention efforts.
- `Impact of Internet Service Type`: Customers using fiber optic internet have a higher churn rate, which could point to service quality or pricing issues with this type of connection.
- `No Add-Ons`: Most churned customers did not subscribe to additional services like online security and tech support, suggesting that bundled services could improve retention.
- `High-Risk Payment Methods`: Customers using electronic checks show a higher churn rate, which could suggest dissatisfaction with billing methods or payment flexibility.

## Recommendations

- **Enhance Retention Among Senior Citizens:**
Develop loyalty programs or personalized offers targeting senior citizens to increase engagement and reduce churn in this demographic.

- **Promote Longer-Term Contracts:**
Consider offering discounts or incentives for customers to switch from month-to-month to longer-term contracts. Highlight the value and savings to encourage commitment.

- **Focus on Payment Method Options:**
Since electronic check users have a higher churn rate, consider educating these customers on more secure or convenient payment options like bank transfers or credit card autopay. Additionally, offering incentives for switching payment methods might improve retention.

- **Engage Paperless Billing Customers:**
Introduce customer engagement programs specifically for paperless billing users. This could involve sending personalized communications, offering exclusive deals, or educating them about additional services.

- **Optimize Service Quality for Internet Customers:**
Fiber optic users show a higher churn rate than DSL users. Investing in improving fiber optic service quality.


