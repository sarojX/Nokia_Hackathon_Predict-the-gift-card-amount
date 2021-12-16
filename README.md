# Nokia_Hackathon_Predict-the-gift-card-amount
Build a machine learning model to predict the Gift_card_amount, given customer engagement information
Problem Description : 
----------------------------------
Predict the gift card amount
Max. score: 100
You are working in an E-commerce company. In this festive season, your company has decided to send gift cards to the customers. 

Task 

You are required to build a machine learning model to predict the Gift_card_amount, given customer engagement information.

Dataset description

The dataset folder contains the following:

train.csv: 12318 x 15
test.csv: 3080 x 14
sample_submission.csv: 5 x 2
The columns provided in the dataset are as follows:

Column name	Description
Customer_ID	Represents a unique identification of a customer
No_of_orders_placed	Represents the total number of orders placed by a customer
Orders_returned	Represents the total number of orders returned  by a customer 
No_of_Review_given	Represents the total  number of reviews given  by a customer
No_of_Comment_added	Represents the total number of comments added by a customer in reviews
No_of_Images_added	Represents the total number of images added by a customer in reviews
No_of_issues_raised	Represents the number of issues or concerns raised by a customer
Sign_up_date	Represents the date when a customer started using the website
Category_of_customers	Represents the category of a customer (active, passive, inactive)
Last_order_placed_date	Represents the last date when the customer placed the order
Gender	Represents the gender of a customer ( male, female )
Premium	Represents whether a customer is a premium member or not
Maximum_bill	Represents the maximum bill (USD) paid by a customer
Minimum_bill	Represents the minimum bill (USD) paid by a customer
Gift_card_amount	Represents the gift card amount (in USD) that can be offered by the company
Evaluation metric

score = max( 0 , 100*(metrics.r2_score(actual, predicted )) )
Result submission guidelines

The index is Customer_ID and the target is Gift_card_amount column. 
The submission file must be submitted in .csv format only.
The size of this submission file must be 3080 x 2.
Note: Ensure that your submission file contains the following:

Correct index values as per the test.csv file
Correct names of columns as provided in the sample_submission.csv file

