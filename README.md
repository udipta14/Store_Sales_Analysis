# Store_Sales_Analysis

Click Here 👇<br>
[Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOWY0ZjY5NDMtZDk5Zi00ZTE2LWIxZjgtNzA3ZDMxZmI0NTc5IiwidCI6ImM0YzUzNGFiLTZlMGMtNDRmOC04YzRiLTAxN2ViZWUxZGMxYiJ9)

***Dataset Introduction***

Store Sales Dataset contains two sheets of Data i.e, Orders and Revenue.<br>
**Orders** - This table contains order information like product, customer details, and shipping details like shipping address, package type.<br>
**Revenue** - This table contains Store sales, discounts, shipping charges. Also, it contains the Revenue of orders like Profit, loss, and discount.<br>

***Business Problem***

A Sales Manager wants to understand different priority orders with their order quantities and revenue generation on them to prepare Business Strategy accordingly. They also want to check which region stores are giving good Margins and a consistent number of orders over time.<br>

**Performed Data Transformation on Store Sales Data before building Visuals ->**

1. Cleaned the unnecessary(blank) columns or rows.<br>
2. Splited Column Location in Orders table by using custom delimiter colon (:) and renamed new columns to Region and State.<br>
3. Added a new custom column in the Revenue table named ‘ Discounted Shipping Price’ by using formula (Shipping Cost - Discount).<br>
4. Created an Index Column in the Orders table with name “Order Sl. No” ranging from 1 with increment of 1.<br>
5. Changed Data type of Order ID, Order Sl. No and Customer ID to text in Orders Table.<br>
6. Added a conditional column in the Revenue table named ‘Profitable Order’ with condition Profit > 1000 and provided values as : if Profit > 1000 (Yes) else (No).<br>

**Problem Statement**
1. The Sales Manager liked to know the sales for **Order ID 90193**.<br>
Created a Manual Relationship between two tables Orders and Revenue. <br>
Also created a table visual to find out the Sales of specified order and the answer is below .<br>
-> 6362.85

2. The Sales Manager wanted to find out the total sales based on order priority, region, and customer ID.<br>
   Find out the categories which generated the highest sum of sales.<br>

   Which order priority generated the highest sum of sales?<br>
-> High<br>
   Which region generated the highest sum of sales based on the above category?<br>
-> East<br>
   What is the customer ID which generated the highest sum of sales from the above categories?<br>
-> 68   

3. The Sales Manager liked to see whether Sales Target is achieved or not for the second quarter of the year 2015.<br>
   Find out the total % of increase or decrease of sales over sales target (without % and + sign)<br>
-> 6.13

4. Compare the profit and sales till now.<br>

   Q.1 Find the date where there was the highest sale. -> 02/02/2015<br>
   Q.2 Find the profit for the corresponding date. -> 991.37<br>

5. Sales Manager wants to track profit of specific product which contains name “Newell” and discount is less than 0.03.<br>
   Created a visual and found out the product name which has the highest profit.<br>
   Q.1 Find the full name of the product: -> Newell 335<br>
   Q.2 Find the profit amount. -> 57.8<br>

6. The Sales Manager liked to represent their footprint in different cities online by showcasing the average shipping cost in that respective state.<br>
   Q.1 Find out the state with the highest average shipping cost. -> Vermont<br>
   Q.2 For the state of California, Share the name of the city and its profit which has the highest average shipping cost.<br>
   Enter the city name: -> San Gabriel<br>
   Q.3 Enter the average value of the shipping cost for the above-submitted city: -> 26<br>
   Q.4 Enter the profit for the above-submitted city: -> 4390.97<br>
   <br>
   <br>

For More Enquiry Click On 👉 [LinkedIn](www.linkedin.com/in/udipta-anupam)
