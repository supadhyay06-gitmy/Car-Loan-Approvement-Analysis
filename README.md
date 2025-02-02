FIRST SCENERIO

Car Loan Approvement Analysis and RCA*

Objective: To understand the Lead to Disbursal Funnel.

Data Explanation:

Attached file contains 4 columns:
User_id- Unique customer id
Risk Bucket - Ranking of user profile ( A being best , E being worst)
Rate_of_interest - Pitched rate of interest for the loan
Cibil_Bucket - Higher the cibil score less risky is the user
Car Selling Price - Price of the car that the user is interested to buy
Disbursable Loan Amount - How much of the car's value can be given as loan to the user
An ideal conversion funnel is : Login -> Credit_approved -> Agreement Created -> Disbursed 

Sharing some context to help you understand our business better:
A customer at the credit approved stage is pitched loan terms - Eg. ROI , Disbursable Loan amount (calculated based on the car price)
The loan terms are based on the customer's credit quality - Like risk bucket, Cibil Buckets

Based on above dataset following questions need to answer

Questions: 

We'd like you to analyse the month on month conversion funnel. 
Additionally, please analyze the conversion funnel of July against the previous months and share your insights on the changes observed.

You are expected to share an RCA (data driven) of why the July conversion could have possibly increased or decreased as compared to previous months.







SECOND SCENERIO

SQL Question*

Objective: To understand the Product Purchase and User Retention

Link to the file: https://www.dropbox.com/scl/fi/n76ink8n9ewvdyweakonn/Product_data_Apr_July.csv?rlkey=8qtgn3gfp30jkjyma7umld4c5&st=v3w52199&dl=0

File Name: Product_data_Apr_July

Data Explanation:
User Id - Identifier of a user
Product Id - Identifier of a product
Event - Action done by the user ( View -> User saw the product, ATC -> User added the item to Cart, Buy - User Purchased the product )
Page - The page of which the user was when the action happened ( Product Listing Page - Page on which multiple items are shown, Product Details Page - The page on which a single item is shown along with the item's details, Cart - The Cart Page where all items added to cart are available )
Timestamp - Time at which the event occurred

Write SQL queries to answer the following questions.

1.What are the top three products sold each month??
2.For each month, that is the count of users who added an item to the cart & count of users who bought that item within 3 days of adding it to the cart
3.For each month, what is the M1 retention of users after their first order. A user is considered as retained in M1 if they have purchased a product between 30 to 60 days of their first order
