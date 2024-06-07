# Classification Model for Predicting & Analyzing Churn

## Summary

I was tasked with analyzing the data provided to me by SyriaTel in relation to customers leaving their service. In doing so, I determined that the most important questions to answer were:

1. What is the Baseline Churn Rate?
2. Which features contribute to churn?
3. Which features have the biggest impact on churn?
4. What can be done to identify when a customer is at risk for churn?
5. What can be done to prevent churn?

After developing an appropriate model (XGBoost, using GridSearch CV to tune parameters), I was able to determine that the 4 features with the largest impact on customer churn were:
1. Total Charge
2. High Amount of Customer Service Calls
3. The presence of an International Plan.
4. The presence of a Voice Mail Plan.

Based on these factors, I made the following recommendations for SyriaTel to implement in order to greatly reduce the amount of churn:
1. Improve Customer Service: Get to the root of customers' issues and resolve them.
2. Take a good look at the international plan that is currently offered and see why customers who have it have such a high rate of churn. Change the plan as necessary to prevent this from happening going forward.
3. Change the pricing model from "minutes used" to a flat rate service so that customers will know what to expect to pay each month, while still retaining profit for SyriaTel.
4. Incentivize getting a VoiceMail Plan. Also investigate why it helps retain customers.
5. Put a system into place for identifying when a customer is at high risk for churn and then be proactive in intervening and helping fix anything that may be leading to churn.


