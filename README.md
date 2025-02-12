# Amazon-The-last-mile-analysis
<span style="color:	#008080 ; font-size:20px">Mihaela Strimbeschi</span>

<div style="text-align:center; color:#008080; font-size:20px">
  <h3>Amazon:The Last-Mile Challenges</h3>
</div>

---
<div style="text-align:left; color:	#008080 ; font-size:15px">
<h3>Introduction</h3>
</div>

This analysis examines Amazon delivery data, including order details, delivery agents' demographics and ratings, locations, environmental conditions (weather, traffic), vehicle types, and delivery times. The goal is to assess key factors affecting delivery efficiency and identify opportunities for optimization.

---

<div style="text-align:left; color:	#008080 ; font-size:15px">
<h3>Objective</h3>
</div>

The objective of this analysis is to identify the factors affecting delivery efficiency and propose solutions for optimization. The analysis is structured around several categories: agent characteristics, external conditions (traffic, weather), and delivery area.

<div style="text-align:left; color:	#008080 ; font-size:15px">
<h3>Questions</h3>
</div>

To achieve this objective, I would like to answer the following questions to identify key factors influencing delivery performance and potential areas for optimization.

---

   1. What is the relationship between the agent’s age and delivery time?
   2. How does the agent’s rating influence delivery time?
   3. Which agents deliver the fastest, and what are their characteristics?
   4. Are there performance differences between agents with similar ratings but different ages?
   5. Which time intervals have the highest average delivery times?
   6. On which days of the week are delivery times higher?
   7. How does delivery performance vary across different geographic zones?
   8. How do different weather conditions impact delivery times?
   9. Which traffic conditions lead to the highest delivery times?

---



<div style="text-align:left; color:	#008080 ; font-size:15px">
<h3>About the Dataset</h3>
</div>

This Amazon Delivery Dataset provides a comprehensive view of the company's last-mile logistics operations. It includes data on over 43,632 deliveries across multiple cities, with detailed information on order details, delivery agents, weather and traffic conditions, and delivery performance metrics. The dataset enables researchers and analysts to uncover insights into factors influencing delivery efficiency, identify areas for optimization, and explore the impact of various variables on the overall customer experience.

---

[Link data Kaggle](https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset/data)

---

**Column Descriptors**

1. ***Order_ID*** – Unique identifier for each order
2. ***Agent_Age*** – Age of the delivery agent
3. ***Agent_Rating*** – Rating or performance score of the delivery agent
4. ***Store_Latitude*** – Geographic coordinates of the store where the order was placed
5. ***Store_Longitude*** – Geographic coordinates of the store where the order was placed
6. ***Drop_Latitude*** – Geographic coordinates of the delivery location
7. ***Drop_Longitude*** – Geographic coordinates of the delivery location
8. ***Order_Date*** – Date when the order was placed
9. ***Order_Time*** – Time when the order was placed
10. ***Pickup_Time*** – Time when the order was picked up for delivery
11. ***Weather*** – Weather conditions during the delivery (e.g., sunny, rainy, snowy)
12. ***Traffic*** – Traffic conditions during the delivery (e.g., low, medium, jam)
13. ***Vehicle*** – Type of vehicle used for the delivery (e.g., van, motorcycle, bicycle, scooter)
14. ***Area*** – Area where the delivery took place (Urban, Metropolitan, etc.)
15. ***Delivery_Time*** – Time taken to complete the delivery
16. ***Category*** – Product category of the ordered item (e.g., electronics, apparel, groceries)

---
