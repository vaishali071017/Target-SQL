# Target-SQL
![image](https://github.com/user-attachments/assets/292f9237-6237-40c9-9133-d9d5fa487f9b)

**About Target:**

Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.
This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

**Business Problem:**

By analyzing this extensive dataset, it becomes possible to gain valuable insights into Target's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

**Features	Description**

customer_id	ID of the consumer who made the purchase
customer_unique_id	Unique ID of the consumer
customer_zip_code_prefix	Zip Code of consumer’s location
customer_city	Name of the City from where order is made
customer_state	State Code from where order is made (Eg. são paulo - SP)
seller_id	Unique ID of the seller registered
seller_zip_code_prefix	Zip Code of the seller’s location
seller_city	Name of the City of the seller
seller_state	State Code (Eg. são paulo - SP)
order_id	A Unique ID of order made by the consumers
order_item_id	A Unique ID given to each item ordered in the order
product_id	A Unique ID given to each product available on the site
seller_id	Unique ID of the seller registered in Target
shipping_limit_date	The date before which the ordered product must be shipped
price	Actual price of the products ordered
freight_value	Price rate at which a product is delivered from one point to another
geolocation_zip_code_prefix	First 5 digits of Zip Code
geolocation_lat	Latitude
geolocation_lng	Longitude
geolocation_city	City
geolocation_state	State
order_id	A Unique ID of order made by the consumers
payment_sequential	Sequences of the payments made in case of EMI
payment_type	Mode of payment used (Eg. Credit Card)
payment_installments	Number of installments in case of EMI purchase
payment_value	Total amount paid for the purchase order
order_id	A Unique ID of order made by the consumers
customer_id	ID of the consumer who made the purchase
order_status	Status of the order made i.e. delivered, shipped, etc.
order_purchase_timestamp	Timestamp of the purchase
order_delivered_carrier_date	Delivery date at which carrier made the delivery
order_delivered_customer_date	Date at which customer got the product
order_estimated_delivery_date	Estimated delivery date of the products
review_id	ID of the review given on the product ordered by the order id
order_id	A Unique ID of order made by the consumers
review_score	Review score given by the customer for each order on a scale of 1-5
review_comment_title	Title of the review
review_comment_message	Review comments posted by the consumer for each order
review_creation_date	Timestamp of the review when it is created
review_answer_timestamp	Timestamp of the review answered
product_id	A Unique identifier for the proposed project.
product_category_name	Name of the product category
product_name_lenght	Length of the string which specifies the name given to the products ordered
product_description_lenght	Length of the description written for each product ordered on the site
product_photos_qty	Number of photos of each product ordered available on the shopping portal
product_weight_g	Weight of the products ordered in grams
product_length_cm	Length of the products ordered in centimeters
product_height_cm	Height of the products ordered in centimeters
product_width_cm	Width of the product ordered in centimeters

**Assumptions**

•	Considering, once the payment has been received for any purchase order that order is called as placed order. And not taking order status as cancelled and unavailable for placed orders.

🙇 To view the SQL Query please click [here](https://github.com/vaishali071017/Target-SQL/blob/main/TARGET%20SQL.pdf)

💡 **Insights & Recommendations**

**Insights**

1. Order Trends: There is a growing trend in the number of placed orders, indicating increased online shopping convenience.

2. Monthly Seasonality: In 2016, October had the highest number of orders due to Halloween. In 2017, November saw the highest orders due to multiple events such as Black Awareness Day and New Year celebrations.

3. Order Timing: Brazilian customers predominantly place orders at night, suggesting convenience-based purchasing.

4. Regional Trends: São Paulo has the highest number of orders and customers. This correlation indicates a strong market presence in the state.

5. Cost Trends: The cost of orders increased by 136.98% from 2017 to 2018 (January to August).

6. Order Value: São Paulo has the highest total value and lowest average price and freight. Paraíba has the highest average order price, while Roraima has the highest average freight value.

7. Delivery Efficiency: There were 6,535 delayed deliveries versus 89,941 on-time deliveries. São Paulo has the fastest average delivery time, while Roraima has the slowest.

8. Payment Preferences: Credit cards are the most common payment method, with most orders associated with single payment installments.

**Recommendations**

1. Promotional Strategies: Offer discounts and combos during festival months using the "Anchored Price" concept to boost orders and sales.

2. Targeted Marketing: Align marketing strategies with peak times and customer behavior to maximize reach and sales.

3. Vendor Partnerships: Partner with more vendors to offer a broader range of products and competitive pricing, potentially increasing order count.

4. Future Planning: Prepare for increased orders in upcoming years with targeted marketing campaigns and social media engagement.

5. Logistics Improvement: Enhance logistics and shipping processes by refining routes and partnering with additional courier services to improve delivery times and customer satisfaction.
