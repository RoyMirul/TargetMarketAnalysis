# TargetMarketAnalysis

You have been provided with information about the customers' historical purchase as the amount of money spent, Number of inactive months and so on. Two columns Potential_Customer and Cust_Last_Purchase represent the customers' respond to the latest advertisement. The column Potential_Customer represents if the customer purchased any product, and the column Cust_Last_Purchase represents the amount of this purchase and it is Nan if there has been no purchase.

Objective
1. Design a predictive model to determine the potential customers who will purchase if you send the advertisement . The target variable is Potential_Customer.

2. Calculate the value and the revenue of your model. Fit your model on train set. Assume amonge the customers on your test set we only send advertisement to those your model predicted as Class1 and we ignore the rest. From the data you can calculate the average Cust_Last_Purchase for those who are in the train set and had the last purchase (Cust_Last_Purchase>0) . Assume sending advertisement to each customer costs 5$ and the average purchase you calculated on the train set remains the same for the test set. Calculate the value of your models to choose the best model.

3. Compare your best model's revenue with the revenue of the default solution which is sending advertisement to all the customers in X_test. Which solution would you choose?

4. Assume the next time you want to target a group of 30,000 customers simillar to this group. And assume the purchase rate is  10 which means 10 out of 100 people who receive the advertisement will purchase the product. Also assume your model will have the same Precision and Recall for Class1 . Will you send the advertisement to everyone, or you use one of the models you have already created?
