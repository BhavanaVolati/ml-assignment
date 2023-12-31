<h1>Housing Dataset:</h1>
<h2>Dataset description:</h2>
California Housing dataset with 10 attributes: longitude, latitude, housing_median_age, total_rooms ,total_bedrooms, population, households, median_income, median_house_value, ocean_proximity; and 20641 readings with varied number of records for each class of ocean_proximity.

<h2>Methodology:</h2>
Bagging and Random Forest is used for ensembling.

<h2>GridSearchCV:</h2>
Approach: It exhaustively searches through a predefined set of hyperparameter values. Method: It evaluates the model's performance for every possible combination of hyperparameter values specified in a grid. Pros: Guarantees finding the best combination if it exists within the specified grid. Cons: Can be computationally expensive, especially when the hyperparameter space is large.

<h2>RandomizedSearchCV:</h2>
Approach: It randomly samples hyperparameter values from a distribution (specified by the user) over a fixed number of iterations. Method: It evaluates the model's performance for a random subset of hyperparameter combinations. Pros: More efficient for large hyperparameter spaces, as it doesn't need to explore all possibilities. Cons: It might not find the optimal combination, but it can often discover good configurations more quickly.

<h2>Conclusion:</h2>
RandomizedSearchCV is a more efficient alternative to GridSearchCV, particularly in scenarios where the hyperparameter space is large, and an exhaustive search becomes impractical.

--------------------------------------------------------------
<h1>Customer Churn Dataset</h1>
<h2>Dataset Descripiton:</h2>
Customer Churn data is collected as .csv file format whixh has 12 attributes: CustomerID, Age, Gender, Tenure, Usage, Frequency, Support, Calls, Payment, Delay, Subscription, Type, Contract Length, Total Spend, Last Interaction, Churn.

<h2>Methodology</h2>
The customer churn data represents the rate at which customers stop using a company's

products or services within a specific period. Churn is an important metric for businesses as it directly impacts revenue, growth, and customer retention.

In the context of the Churn dataset, the churn label indicates whether a customer has churned or not. A churned customer is one who has decided to discontinue their subscription or usage of the company's

services. On the other hand, a non-churned customer is one who continues to remain engaged and retains their relationship with the company.

By analyzing churn behavior and its associated features, companies can develop strategies to retain existing customers, improve customer satisfaction, and reduce customer turnover. Predictive modeling

techniques can also be applied to forecast and proactively address potential churn, enabling companies to take proactive measures to retain at-risk customers.

The goal of this notebook is to discover insights by performing customer segmentation using k-means clustering algorithm and building the classification model to predict the churn probability.

<h2>Conclusion</h2>
According to the explainer above, we can draw the following conclusions
1.Female customers prone to churn more than male. 2.Customer with age more than an average (40 years old) has higher probability of churn. 3.Customer with short-term contract (Monthly contract) tends to churn more than customer with long-term contract (Quaterly and Annual) 4.Customer who call for supports more than four times increase the probability of churn. 5.Customer with payment delay higher than an average of the sample (12 months) has higher proablity to churn. 6.Customer with lower spending score tends to churn more than customer with higher spending score. 7.Customer with up to date interaction tends to churn less.​
