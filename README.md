# Hotel-Booking-Analysis

Welcome to the Hotel Booking Analysis project! This repository contains an in-depth examination of hotel booking data to derive meaningful insights that can help drive strategic decision-making in the hospitality sector. The analysis includes various visualizations and findings related to Average Daily Rate (ADR), customer types, reservation statuses, and more.

# Project Background

This analysis focuses on hotel booking data for two types of hotels: City Hotel and Resort Hotel. The goal is to understand customer behavior, pricing strategies, and overall performance metrics. Key business metrics for evaluation include Average Daily Rate (ADR), customer types, cancellation rates, and average days in waiting lists.


Insights and Recommendations are Provided on the Following Key Areas:

* Average Daily Rate (ADR) Analysis
* Customer Type Insights
* Reservation Status Analysis
* Waiting List Durations

The Python script used for data inspection and cleaning can be found here: [[Hotel Booking Analysis Notebook](./hotel-booking.ipynb)].

Data Structure & Initial Checks

The main data structure consists of one table with a total row count of 119391 records. 
A brief description of the table is as follows:

hotel_data: Contains booking transactions, including ADR, customer types, and reservation statuses, customer demographic details, including customer types and preferred stay periods.

Raw data can be found here: [[Raw Data File](./hotel_bookings.csv)]


# EXECUTIVE SUMMARY

# Overview of Findings

The analysis reveals significant trends in hotel booking performance, customer behavior, and pricing strategies. Key takeaways for stakeholders include:

* ADR Comparison: 
Resort Hotel has a higher ADR during the months of May to September, indicating a peak season. City Hotel also shows elevated ADR from May to August, but significantly lower than Resort Hotel.

* Customer Types: 
The highest customer type is transient in both hotels, with a preference for weeknight stays. City Hotel has higher numbers of check-outs and cancellations, while Resort Hotel exhibits a higher average lead time.

* Reservation Statuses: 
Transient customers show more check-outs and cancellations. Additionally, customers with no deposits have higher reservation rates across all hotels.

* Waiting List Durations: 
Average days on the waiting list are higher in City Hotel than in Resort Hotel.


# Insights Deep Dive

# Average Daily Rate (ADR) Analysis

Peak Periods: Resort Hotel has the highest ADR during the 7th to 9th months of the year, while City Hotel shows elevated ADR from May to August.

![ADR by month   hotel type](https://github.com/user-attachments/assets/115b4324-31e9-4e5b-85bb-3eb908abe209)

# Customer Type Insights

Customer Preferences: Transient customers are the most common, with a preference for weeknight stays.

![Customer type vs hotel type](https://github.com/user-attachments/assets/dc74ed5b-5d2d-4c72-aa6f-0b065fcaa28a)


Lead Time Analysis: Resort Hotel has a higher average lead time, with contract customers showing the highest average lead time, followed by transient-party customers.

![avg lead time by customer types](https://github.com/user-attachments/assets/aeb487c1-7118-410f-81d4-7524a3fb195f)


# Reservation Status Analysis

Cancellation Trends: City Hotel has a higher number of check-outs and cancelled reservations, particularly among transient customers.

![reservation status by deposti and hotel types](https://github.com/user-attachments/assets/05707bc2-6464-4f19-9607-b6833fb6cbc1)


Deposit Relationship: The analysis indicates that reservations with no deposits are more common across all hotels.

![deposit types vs reservation status by hotel type](https://github.com/user-attachments/assets/25faa69e-386e-4b95-8161-e7963ef25454)


Waiting List Durations

Comparison of Waiting Lists: The average days on the waiting list are higher for City Hotel compared to Resort Hotel.

![Average days in waiting list by hotel types](https://github.com/user-attachments/assets/546134bb-498b-4170-a4d1-2c4bd625144e)




# Recommendations

Based on the insights and findings above, we would recommend the marketing and sales teams to consider the following:

* Pricing Strategies: Explore dynamic pricing strategies during peak months for Resort Hotels to maximize revenue.

* Targeted Marketing: Develop tailored marketing campaigns focused on transient customers and promote weeknight stays.

* Improve Cancellation Policies: Investigate the reasons behind cancellations and improve policies to reduce their occurrence.

* Utilize Waiting List Data: Leverage insights from waiting list durations to enhance customer satisfaction and manage bookings more effectively.


# Assumptions and Caveats

Throughout the analysis, several assumptions were made to manage data challenges:

* Assumption: Missing customer demographic records were inferred based on overall trends observed within the dataset.
* Assumption: Records with non-sensical values were excluded to maintain data integrity.
