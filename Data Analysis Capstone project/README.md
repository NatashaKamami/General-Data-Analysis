# ANALYSIS OF SALES DATA
## Business Problem : Understanding Sales Performance and Customer Behaviour
The dataset and the visualizations generated from the data, collectively aim to analyze how various factors such as promotions, order types, product categories, shipping methods and customer preferences, impact overall sales performance. By examining these relationships, the business will be able to identify strategies that will maximize sales as well as improve customer satisfaction.


## Data
The Data used is from: https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data.
This dataset provides an in-depth look at e-commerce sales from Amazon India. 
It contains data in the following columns:

- **Order_ID**: Unique identifier for each order.
- **Date**: Date of the sale.
- **Status**: Status of the sale (e.g. Shipped, Cancelled).
- **Fulfilment**: Method of fulfillment (e.g. Merchant).
- **Ship_service_level**: Type of shipping service used (e.g. Standard).
- **Style**: Style of the product.
- **SKU**: Stock Keeping Unit, unique identifier for each product.
- **Category**: Product category (e.g. Kurta).
- **Size**: Size of the product (e.g. S, M, L).
- **ASIN**: Amazon Standard Identification Number.
- **Courier_Status**: Status of the courier.
- **Qty**: Quantity of the product.
- **Amount**: Amount for the sale.
- **Ship_city**: Shipping city.
- **Ship_state**: Shipping state.
- **Ship_postal_code**: Shipping postal code.
- **Ship_country**: Shipping country.
- **Promotion_applied**: Indicates whether a promotion was applied.
- **Order_type**: Type of order (e.g. B2B Sale or B2C Sale).


## SQL Database Design

![image](https://github.com/user-attachments/assets/73c1ca46-5367-4b0c-8999-cb6ec6c9a47d)

## SQL queries from Big Query

![image](https://github.com/user-attachments/assets/ebb61bd0-35c5-4304-ae6e-43eb4d86f143)


## Tableau Visualizations
Link to my Tableau Story : https://public.tableau.com/app/profile/natasha.kamami/viz/Amazon_Sales_17301907475480/Story1

1. **Line Graph to show Monthly Sales Trends**: Displays sale trends over time.

![image](https://github.com/user-attachments/assets/9d4e6b56-1446-4744-8535-6c23c86c3a96)

![image](https://github.com/user-attachments/assets/3829e145-a868-4386-b901-3c5085098a19)


The line graph shows monthly sales for the year 2022 . We can see that sales were generally low at the beginning of the year but they suddenly shoot up in April to where they peak, before dropping again and staying low for the rest of the year. The peaking of the sales amount in April may be attributed to the Ram Navami celebrations which were observed with various festivities around India. This likely led to an increase in purchases of clothing and traditional attires, including ethnic wear like Kurtas, for the festivals. This is shown in the second bar chart where Kurtas were the second best selling product category in April. The visualization is important in identifying seasonality in the sales amounts. It will also help in forecasting and in planning future inventory needs, so that the business can capitalize fully during peak times and mitigate downturns. 

2. **Bar Chart to Investigate Impact of Promotions on Sale Amount**: This visualization illustrates how promotions affect sales amounts.

![image](https://github.com/user-attachments/assets/983de458-cabe-4e92-9cb5-0c3b809857d6)

This bar chart highlights the impact of promotions on the sales amount. We can tell that the amount of sales when a promotion is applied is significantly higher than the amount of sales when no promotion is applied. This visualization is important in helping the company evaluate the effectiveness of promotions and this will help improve their marketing strategies in the future which will consequently boost their sales.

3. **Bar Chart to Investigate Effect of Order Type on Sale Amounts**: Analyzes the sales performance of different order types.
 
![image](https://github.com/user-attachments/assets/93147f6d-277c-48e5-8d65-6e8e38017e11)

This bar chart shows the distribution of total amount of sales depending on the order type; either Business to Business(B2B) sales or Business to Customer(B2C) sales. From the chart, B2C sales were a lot higher in comparison to B2B sales. This information will help the company identify which order type is more profitable than the other. Understanding this will guide sale strategies which will enable the company to tailor promotions specifically to the most profitable order type, thus enhancing customer targetting and improving overall sales as well.

4. **Combined Bar Chart of Sale Amounts and Quantity by Category**: Shows the relationship between sales amounts and quantities across product categories.
   
![image](https://github.com/user-attachments/assets/f2774e0f-7948-4581-bf58-ffa4d5c16048)

This bar chart shows which product categories sell the most units and consequently contribute the most revenue. From our visualization we can tell that Set and Kurta are the top 2 best performing categories in terms of total sales as well as quantity. This visualization will not only help in understanding demand trends, but it will also be useful in inventory management by highlighting which categories need more stock, and which ones could benefit from promotions in order to boost their sales. 

5. **Bar Chart of Quantity by Ship Service Level**: Assesses the efficiency of shipping service levels based on the quantity of products sold.

![image](https://github.com/user-attachments/assets/64a9c803-7269-49fc-a0ab-64e04072e0a9)

This bar chart focuses on the relationship between different ship service levels and the quantities sold. From the visualization, we can tell that a lot of customers prefer expedited shipping over standard shipping. This visualization will help the business understand customer preference when it comes to shipping options. With this information, the company will be able to offer better logistic services to customers which will enhance customer satisfaction and consequently increase sales. 

6. **Pie Chart for Different Size Groups According to Total Quantity**: Illustrates how different size groups compare in terms of total quantity sold.

![image](https://github.com/user-attachments/assets/e93e620c-a34c-4893-aaf0-b73831bd4b36)

The pie chart illustrates the distribution of sale quantities across different sizes. We can see that sizes M, L and XL are the most preffered sizes by customers. This information will help in understanding customer preferences and in managing inventory for specific sizes. The company can ensure that popular sizes are always in stock while reducing overstocking for the less popular sizes.

## Next Steps for the Project

**Identifying Data Gaps and Opportunities to be Explored**

- **Customer Demographics**: Lack of information on customer demographics such as age or gender makes it hard to fully understand customer preferences and behaviours. Adding demographic data will therefore help the company target different groups more effectively.

- **Detailed Shipping Metrics**: Lack of data on shipping times and customer feedback on delivery, limits our understanding of fulfillment efficiency and customer satisfaction. By tracking shipping performance metrics, such as average delivery times, we can improve logistics and customer satisfaction as well.

By addressing the above gaps and exploring these opportunities, the business can gain deeper insights on sales, improve efficiency, and enhance customer satisfaction.

