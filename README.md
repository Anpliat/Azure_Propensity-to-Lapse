# Propensity to Laps (Microsoft Azure)

### Concept:
A Loyalty business partner has shared their raw customer transaction data with us with the intent to analyze and predict customer churn. The firm runs a successful reward system where the customers collect points from flights or purchases from affiliated partners (e.g. Tesco or Apple etc) which they then redeem to book flights, hotels or rent a car. Here, after conducting the data and feature engineering process we have resulted in the given dataset. The State field (Label) is the customer current lapsing status (Active or Lapsed converted in a Boolean form – Active= 0, Lapsed=1).

### Task:
Build a Machine Learning Model, using the Azure Machine Learning Studio as a working environment, that successfully predicts if a customer with the given characteristics will Lapse in the next 12 months.

### Dataset:
The given dataset consists of 5000 observations (customers) having the below fields (characteristics):
* State: Lapsed status (Active= 0, Lapsed=1)
* Sum_collect: how many times a customer collected
* Sum_redeem: how many times a customer redeemed
* Sum_collect_points: how many points a customer has collected in total
* Sum_redeem_points: how many points a customer has redeemed in total
* Years_in_the_program: years since customer’s registration to the program
* Months_since_last_transaction: months passed since customer’s last action (collection or redemption)
