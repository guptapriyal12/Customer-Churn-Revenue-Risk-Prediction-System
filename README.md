# Customer-Churn-Revenue-Risk-Prediction-System
## Business Context
This project focuses on a subscription-based business model where customer retention is critical for sustainable revenue growth.

## Problem Definition
Customer churn leads to significant recurring revenue loss. Existing churn prediction systems focus only on binary churn classification and fail to account for revenue impact, prioritization, and explainability.

## Objective
The objective of this project is to build an intelligent customer churn and revenue risk prediction system that:
- Predicts churn probability
- Estimates revenue at risk
- Explains key drivers of churn
- Monitors model performance over time

## Churn Definition
A customer is considered churned if they cancel their subscription, fail to renew their contract, or remain inactive beyond a defined threshold period.

## Revenue Risk Definition
Revenue risk is defined as the expected financial loss if a customer churns and is calculated as:
Revenue Risk = Churn Probability × Customer Revenue

## Hypotheses
1. Customers with declining engagement trends are more likely to churn than customers with stable usage.
2. Revenue-weighted churn prioritization improves retention ROI.
3. Model performance degrades over time due to changes in customer behavior.

## Success Metrics
- Recall@Top-K customers
- Revenue at risk
- Lift over random targeting
