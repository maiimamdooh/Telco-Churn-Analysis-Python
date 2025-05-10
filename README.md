# Telco-Churn-Analysis

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

  
## Recommendations

- `Contract Optimization`:
   Offer incentives for customers to switch from month-to-month to longer-term contracts.
- `Service Enhancement`:
   Improve fiber optic service quality to reduce dissatisfaction.
- `Payment Method Strategy`:
   Educate electronic check users on secure and flexible payment options.
- `Customer Retention Programs`:
  Introduce loyalty programs targeting senior citizens and paperless billing users.
- `Value-Added Services`:
   Promote Online Security and Tech Support to reduce churn.

## Conclusion
The analysis highlights a 26.5% churn rate driven by high costs, short contracts, and lack of service add-ons. Strategic improvements in contract structures, service quality, and customer engagement can enhance retention and long-term revenue growth.
