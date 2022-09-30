# **Swift Meal App Data Analysis**

![image](https://user-images.githubusercontent.com/91932634/193319972-b17fbc22-e52b-458e-97bd-da10989ccd07.png)

--- Richards Okiemute

richards.okiemute@gmail.com

**Scenario**

The number of food outlets in New York is experiencing a steady daily rising in number. A lot of professionals, workers, students depend on these food outlets to carter for their daily food requirements due to their tight schedules. Having access to an online food delivery app is a great solution to their challenges because it provides them wth the choice to make delivery from any food outlet of their choice with ease. An online food food aggregator start-up; Swift-Meal, proffers access to different food outlets through the use of a mobile app.

With the mobile app, customers can make swift orders, link a delivery person to the order and guides the delivery person to the customer. The delivery person confirms the pick-up and drop-off of each order. The app also records the delivery time, preparation time and the customer service ratings. Swift-Meal generates revenue by collecting a fixed margin of the delivery order from various food outlets.

**Objective**

The Swift-Meal has stored the data of the different orders made by the registered customers in her online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience.

**Data Analyst Tasks**

* Analyze the data to uncover useful insights from the data.

* Answer Business questions through analysis.

* Reach reasonable conclusions and proffer recommendations that will help improve the business.

**Data Information**

The data contains the different data related to a food order. The various features are described below in the data columns.

**Data Columns**

**day_of_the_week:** Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
**rating:** Rating given by the customer out of 5
**food_preparation_time:** Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
**delivery_time:** Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
**order_id:** Unique ID of the order
**customer_id:** ID of the customer who ordered the food
**restaurant_name:** Name of the restaurant
**cuisine_type:** Cuisine ordered by the customer
**cost_of_the_order:** Cost of the order


**Business Questions**

*Run a summary statistics on the dataset and give your observations*
* What is the number of unrated orders?
* Explore all the variables and provide observations on the distributions of all the relevant variables in the dataset
* What are the top 5 restaurants that have received the highest number of orders?
* What is the most popular cuisine on weekends?
* What is the number of total orders where the cost is above 20 dollars? What is the percentage of such orders in the dataset?
* What is the mean delivery time based on this dataset?
* The company has decided to give a free coupon of 15 dollars to the customer who has spent the maximum amount on a single order. Write the code to find the * ID of the customer along with the order details
* Perform bivariate/multivariate analysis to explore relationships between the important variables in the dataset
* The company wants to provide a promotional offer in the advertisement of the restaurants. The condition to get the offer is that the restaurants must have a rating count of more than 50 and the average rating should be greater than 4. Write the code to find the restaurants fulfilling the criteria to get the promotional offer
* The company charges the restaurant 25% on the orders having cost greater than 20 dollars and 15% on the orders having cost greater than 5 dollars. Write the code to find the net revenue generated on all the orders given in the dataset
* The company wants to analyze the total time required to deliver the food. Write the code to find out the percentage of orders that have more than 60 minutes of total delivery time
* The company wants to analyze the delivery time of the orders on weekdays and weekends. Write the code to find the mean delivery time on weekdays and weekends
Give your conclusions and business recommendations derived from the analysis
