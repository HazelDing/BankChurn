# Bankchurn Analysis
I. Project Review:

This project addresses the pressing challenge of credit card customer churn in a banking institution, where a
growing number of customers are discontinuing their credit card services. The objective is to investigate the root causes of
churn and develop a robust churn prediction model using machine learning techniques. The study aims to identify high-risk
customer segments, pinpoint key factors influencing churn, assess the accuracy of the chosen models (Random Forest
Classification and Artificial Neural Network), and propose actionable strategies for retaining high-risk customers. The
anticipated outcome is the development of an accurate churn prediction model that empowers the bank to proactively engage
with customers, enhance services, and minimize customer attrition, ultimately contributing to a substantial reduction in churn
rates and improved overall customer retention.

II. Choice of Model:

a. Artificial Neural Network (ANN) model

b. Random Forest Classification model

III. Data Science Pipeline

A. Data Collection

B. Data Preparation

C. Exploratory Data Analysis (EDA)

D. Future Engineering

E. Machine Learning Model

F. Model Evaluation

IV Conclusion:

Our analysis leads us to the determination that the Random Forest model outperforms the ANN model in terms of accuracy. Moreover, the Random Forest model provides a valuable feature ranking, offering insights into the importance of different features in determining churn rates.

V Business Insights:

1. Focus on transaction activity
Total_Trans_Ct (Total transaction count in the last 12 months) is the most important feature for predicting churn.
The bank should encourage and incentivize customers to maintain an active transaction history. Offer rewards, discounts, or exclusive benefits for customers with higher transaction counts.

3. Address changes in transaction behavior
Total_Ct_Chng_Q4_Q1 (Change in transaction count over the last quarter) is the second important indicator of changing transaction behavior.
The bank should monitor and analyze customers experiencing significant changes in their transaction patterns. Implement targeted marketing campaigns to re-engage customers showing a decline in transaction counts.

4. Manage revolving balances
Total_Revolving_Bal (Total revolving balance on the credit card) is also a key factor, indicating unpaid debt that carries over to the next month.
The bank needs to provide personalized financial counseling or debt management services to customers with high revolving balances. Introduce balance transfer options or promotions to help customers reduce revolving debt.

5. Consider demographic factors
Combined with EDA we did, categorical variables like gender and the number of dependents also play important roles in churn rate [2].
The bank needs to customize retention strategies based on demographic information. For example, tailor marketing messages and loyalty programs to specific gender preferences or family-oriented incentives for customers with dependents.

VI IEEE Machine Learning Report

![image](https://github.com/HazelDing/BankChurn/assets/149340952/7867b733-adb7-4550-9242-e4c60e93cfa4)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/bec4670c-b5d6-4d29-9592-5f37c4fe24b9)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/6d887b75-9c3e-47c9-a555-0e0076f8e146)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/4793f48d-e057-4ff6-8a52-914d80994d06)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/097cc205-db71-4b7c-99b6-9c1c150021ba)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/89c02485-cefb-4be5-b245-b2f99ad810b2)

![image](https://github.com/HazelDing/BankChurn/assets/149340952/863f10f2-766d-4e0c-9630-4dd71179d36d)







