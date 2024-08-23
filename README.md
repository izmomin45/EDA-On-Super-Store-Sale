#Data Description
This analysis focuses on an EDA (Exploratory Data Analysis) of a dataset containing various aspects of sales and customer orders. The goal is to uncover insights related to order patterns, profitability, customer preferences, and other key metrics.

  #Columns Description
  
1] Order ID: (String) Unique identifier for each order.

2] Order Month: (Date) The month when the order was placed.

3] Ship Mode: (String) The shipping method chosen for the order.

4] Payment Mode: (String) The payment method used by the customer.

5] Product Category: (String) The category of the product ordered.

6] Quantity: (Integer) The number of units ordered.

7] Profit: (Float) The profit earned from the order.

8] Total Sale: (Float) The total sales value of the order.

9] State: (String) The state where the order was delivered.

10] Region: (String) The region of the delivery address.

11] Customer ID: (String) Unique identifier for each customer.

Questions and Answers

1] E1] What is the total number of orders placed?

Ans E1] 3003
2] E2] Which Ship Mode is most frequently used?

Ans E2] Standard Class (3451 orders)
3] E3] What is the average Sale amount across all orders?

Ans E3] $265.34
4] E4] What is the most common Payment Mode used by customers?

Ans E4] COD (Cash on Delivery)
5] E5] What is the most common Product Category purchased?

Ans E5] Office Supplies (close to 3500 orders)
6] E7] No of Customers

Ans E6] 773
7] E8] Which State has the highest number of orders?

Ans E8] California (1189 orders)



1] M1] How does the average Profit vary across different Product Categories?

Ans M1] Technology has the highest average profit.
2] M2] How does the average Sale differ between Segments?

Ans M2] The corporate segment has the highest average sale.
3] M3] Which top 5 Cities have the highest Total Sale?

Ans M3] Albuquerque has the highest total sale.
4] M4] How does the Day For Delivery impact the Profit?

Ans M4] The 8th day has the most profitable deliveries.
5] M5] What is the distribution of Order Month across different Regions?

Ans M5] November, September, and December have the most orders.
6] M6] How does the average Quantity ordered vary across different Sub Categories?

Ans M6] The average quantity ordered is between 3 to 4 units.
7] M7] How does Total Sale vary by Region?

Ans M7] The West region has the highest total sales, while the South has the lowest.

1] H1] What is the relationship between Ship Mode and Profit?

Ans H1] Standard Class is more profitable.
2] H2] How does the Sale amount change over time across different Regions?

Ans H2] The West region shows the highest sales over time.
3] H3] Which State sees the highest Profit?

Ans H3] California has the highest profit.
4] H4] How does the Sale distribution vary between different Sub Categories?

Ans H4] The Binders subcategory has the highest sales distribution.
5] H5] What is the trend of Total Sale over different Order Months?

Ans H5] The total sale shows a consistent trend with peaks in certain months, likely during November and December.
6] H6] Is there a significant difference in Profit between orders with different Quantity ranges?

Ans H6] Higher quantities generally lead to higher profits.



# Key Points or Insights from the Data
1] **Order Volume:** California leads in the number of orders, and November, September, and December are peak months.

2] **Ship Mode:** Standard Class is the most frequently used and profitable shipping method.

3] **Product Categories:** Office Supplies are the most commonly purchased, while Technology yields the highest profits.

4] **Payment Preferences:** COD (Cash on Delivery) is the most common payment method.

5] **Regional Performance:** The West region consistently outperforms others in both sales and profit.

6] **Profit Trends:** Higher quantities and specific days of delivery (like the 8th day) correlate with increased profitability.

7] **Customer Insights:** With 773 customers, understanding their preferences and behavior could further optimize sales strategies.
