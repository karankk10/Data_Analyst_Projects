<h1>E-Commerce Recommendation Engine</h1><p>Leveraging SQL for Personalized Shopping Experiences</p>
<h2>Problem Statement:</h2>
<h4>●	An e-commerce platform wants to enhance its user experience and optimize product recommendations based on user interactions and past purchase history. </br>
●	The platform seeks to identify patterns in user behavior, such as popular products, frequently interacted categories, and purchasing habits, to provide personalized recommendations and improve customer engagement.
</h4>

<h2>Databases Schema</h2>

<h4>Product Table:</h4>

<p>Columns:</br>
●	product_id: Unique identifier for each product.</br>
●	product_name: Name of the product.</br>
●	category: Category to which the product belongs.</br>
●	price: Price of the product.</br>
●	brand: Brand of the product.</p>



<h4>Interactions Table:</h4>

<p>Columns:</br>
●	interaction_id: Unique identifier for each interaction.</br>
●	user_id: Unique identifier for each user.</br>
●	product_id: Unique identifier for each product.</br>
●	interaction_type: Type of interaction (e.g., view, add to cart, purchase).</br>
●	timestamp: Timestamp when the interaction occurred.</p>
.


<h4>Past Purchases Table:</h4>

<p>Columns:</br>
●	purchase_id: Unique identifier for each purchase.</br>
●	user_id: Unique identifier for each user.</br>
●	product_id: Unique identifier for each product that was purchased.</br>
●	purchase_date: Date when the purchase occurred.</br></p>

<h2>Complete SQL Analysis</h2>

1.	Select all records from the Products table</br>
2.	 Filter products by category 'Electronics'</br>
3.	 Sort products by price in descending order</br>
4.	Count the number of interactions</br>
5.	Calculate the total purchase amount for each user</br>
6.	Retrieve the oldest purchase date</br>
7.	Join Products and Interactions to get product details with interaction type</br>
8.	Subquery to find products with more than 10 interactions</br>
9.	Update product price for a specific product</br>
10.	Delete an interaction record</br>
11.	Retrieve the top 5 users with the highest total purchase amount</br>
12.	Count the number of unique brands in the Products table</br>
13.	Window function to rank products by price within each category</br>
14.	Common Table Expression (CTE) to find the average price of products</br>
15.	Create an index on the user_id column of the Past_Purchases table</br>
16.	Retrieve the product with the highest total purchase amount</br>
17.	Create a view to show interactions with product details</br>
18.	Rollback a transaction if an error occurs while updating interactions</br>
19.	Count the number of interactions per product</br>
20.	List top N most popular products based on interactions</br>
21.	Retrieve product details along with user interactions</br>
22.	Find products with no interactions</br>
23.	Rank products by price within each category using window functions</br>
24.	Calculate the cumulative sum of total purchases by user</br>
25.	Find products purchased more than once</br>
26.	Retrieve interactions for products with prices above the average price</br>
27.	Create a CTE to calculate average product price by category</br>
28.	Use a CTE to find the top 3 users with the highest total purchase amounts</br>
29.	Calculate the percentage contribution of each product to the total sales amount</br>
30.	Identify users who made purchases of more than $500 in a single transaction</br>
31.	Calculate the average time between consecutive purchases for each user</br>
32.	Identify products that have been interacted with but not purchased</br>
33.	Find users who made purchases in the first and last quarter of the year</br>
34.	Calculate the average quantity of products purchased by users who interacted with products priced above the average price</br>
35.	Find users who have interacted with products across multiple categories</br>
