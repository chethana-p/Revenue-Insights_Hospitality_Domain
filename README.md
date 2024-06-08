Revenue-Insights-Hospitality-Domain
In this project , we aim to perform the data analysis on AtliQ Grands hospitality company data . Tool used for the analysis are Power BI.

Table of Contents
Business Task
Problem Statement
Data Source
Data Cleaning/Preparation
Live Dashboard
Insights
Recommendations
Limitations
Business Task
To create the metrics according to metrics list and to create the dashboard acording to mockup provided by stakeholders.
To gather relevant insights from the analysis to identify the areas of improvement.
Problem Statement
AtliQ Grands is a well-established hospitality company that owns multiple five-star hotels across India. The company has been in the industry for the past 20 years and is known for its luxury and business hotels. In recent times, AtliQ Grands has faced a decline in its market share and revenue due to strategic moves from competitors and ineffective decision-making in management. To tackle this issue, the managing director of AtliQ Grands has decided to incorporate "Business and Data Intelligence" to regain its market share and revenue. However, the company does not have an in-house data analytics team to provide insights from its historical data. Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

Data Source
Domain:

Hospitality Domain
Dataset Name:

dim_date.csv
dim_hotels.csv
dim_rooms.csv
fact_aggregated_bookings.csv
fact_bookings.csv
metrics list.xlsx
Dataset Type:

CSV Datatypes
Dataset Size:

135k Bookings data spanning 3 months.
Data Cleaning/Preparation
Checked for presence of duplicates and eliminated them.
Removing irrelevant columns.
Data type standardization.
Formatting dates for consistency.
Formatted numerical data for consistency.
Handling the text values.
Handled the null values in rating of hotel column by average imputation.
Created calculated columns using DAX.
Moved all measures to new table dedicated for measures only.
Live Dashboard
Power BI: https://app.powerbi.com/groups/me/reports/e73c5d7c-a2f4-4ed2-a198-8e2aa37da706/ReportSection8d1e1dc9587b4b3dbc7d?experience=power-bi

Insights
insights from the analysis:

Overall 1709 M revenue is generated across 4 cities. Mumbai generates the highest revenue (669 M) followed by Bangalore, Hyderabad and Delhi.
Luxury Category is generating more revenue compared to Business Category.
AtliQ Exotica performs better compared to all 7 type of properties with 320 Million revenue, rating 3.62, occupancy percentage 57 and cancellation rate as 24.4%.
Realisation is 70 % . This means 70 % of booked people have sucessfully stayed and checked mout. 5 % of booking are resulting in no show may be they had some personal reasons.
Almost 25 % bookings are cancelled. Cancellation rate is same across all categories.
ADR is around 12.7k and RevPar is around 7.3k . Revenue increases if the ADR is also Increased.
RevPar, ADR, Occupancy % and Realisation % is almost same for weekday and weekend .
ADR is not fluctuating over the period of time. Its alsmost same for all weeks.
RevPar and Occupancy % are correlated to each other.
Atliq Exotica is generating highest revenue(118M) and Atliq grands in dehli is generating the least revenue(36M).
Realisation % is same across all booking platform. ADR is varying with high ADR in offline booking and low ADR in direct online.
Elite Rooms will generate most revenue followed by premium, presidential and standard.
Recommendations
Dynamic Pricing is the opportunity. Hotels should use the different pricing on weekend and weekday to increase the revenue.
Hotels should adapt to supply and demand concept to increase Revpar and ADR.
First, Atliq have to pick the hotel that is performing the least and it’s the biggest problem statement . If they solve problems in such hotels its overall business goes up.
Online presence is very important and we can increase the occupancy rate if we maintain the good average rating, above 4 considered as good.
In online channels its evident that the probability of booking the hotel room is higher when there is the high average rating. Hotels should work on maintaining good average rating in their booking platforms.
Give promotions or discounts in booking platforms. If hotels increase the occupancy % , their revenue goes up.
Booking Platforms should have user friendly rules and cancellation policies.
Pricing Influeces the occupancy % and vice versa.
Hotels should provide the good customer service. They should work on the customer review.
Get feedbacks from the customers and solve the problems they are facing.
Limitations
Analysis might provide insights at a specific point, continuous monitoring is required.
Analysis is based on the historical data and this may be not true in future.
Size of dataset is just 3 months and we could have identified more trends and patterns with more data collected over period of time.
