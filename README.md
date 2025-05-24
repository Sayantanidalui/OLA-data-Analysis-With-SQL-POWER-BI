# OLA-data-Analysis-With-SQL-POWER-BI
This project analyzes OLA ride data using SQL for Exploratory Data Analysis (EDA) and Power BI for interactive visualization for the month of July 2024. The goal is to discover patterns in ride bookings, success and cancellation, revenue etc. <br>

<b> EDA in SQL </b><br>
Key insights from SQL analysis : <br>
1.	Retrieve all successful bookings :  Over 3166 successful bookings were completed.<br>
2.	Find the average ride distance for each vehicle type:  Prime sedan had the longest average ride distances. <br>
3.	Get the total number of cancelled rides by customer:  523 rides were cancelled by customers. <br>
4.	List the top 5 customers who booked the highest number of rides: Identified top 5 customers based on their booking frequency. <br>
5.	Get the number of rides cancelled by drivers due to personal and car-related issues:  312 such rides retrieve from the data. <br>
6.	Find the maximum and minimum driver ratings  for prime sedan bookings :  minimum rating is 3 and maximum rating is 5 for prime sedan, is identified. <br>
7.	Retrieve all rides where payment was made using UPI :  1284 bookings are retrieve where payment was made through UPI. <br>
8.	Find the average customer rating per vehicle type:  Prime plus had the highest average customer ratings. <br>
9.	Calculate the total bookings value of rides completed successfully :  1734897 total booking value discovered.<br>
10.	List all the incomplete rides along with the reason: 194 bookings found that are incomplete due to several reasons like customer demand or vehicle breakdown.<br>

<b> Power BI Visualization </b><br>
Segregation of the views:<br>
1. Overall - Ride Volume Over Time, Booking Status Breakdown. <br>
2. Vehicle Type - Top 5 Vehicle Types by Ride Distance. <br>
3. Revenue - Revenue by Payment Method, Top 5 Customers by Total Booking Value, Ride Distance Distribution Per Day. <br>
4. Cancellation - Cancelled Rides Reasons (Customer), cancelled Rides Reasons(Drivers). <br>
5. Ratings -  Driver Ratings, Customer Ratings. <br>

Answers: <br>
1. Ride Volume Over Time: A time-series chart showing the number of rides per day/week. <br>
2. Booking Status Breakdown: A pie chart displaying the proportion of different
booking statuses (success, cancelled by the customer, cancelled by the driver, etc.). <br>
3. Top 5 Vehicle Types by Ride Distance: A bar chart ranking vehicle types based on the total
distance covered. <br>
4. Average Customer Ratings by Vehicle Type: A table showing the average
customer ratings for different vehicle types. <br>
5. cancelled Rides Reasons: A pie chart that highlights the common reasons for ride
cancellations by customers and drivers. <br>
6. Revenue by Payment Method: A bar chart displaying total revenue based on
payment methods (Cash, UPI, Credit Card, etc.). <br>
7. Top 5 Customers by Total Booking Value: A leaderboard visual listing customers who have
spent the most on bookings. <br>
8. Ride Distance Distribution Per Day: A bar chart showing the ride distances for different Dates. <br>
9. Driver Rating Distribution: A table visualizing the spread of driver ratings for different
vehicle types. <br>
10. Customer vs. Driver Ratings: A table comparing customer and driver ratings for
each completed ride, analyzing correlations. <br>


This visualization also include interactive features like a date slicer and most importantly some KPIs such as Total booking, succeeded bookings, cancelled bookings, total booking values etc for better understanding. <br>

This project demonstrates the power of combining SQL and Power BI to generate actionable insights for ride sharing platforms and supports in data-driven business decisions.






