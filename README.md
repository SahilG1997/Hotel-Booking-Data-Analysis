# Hotel-Booking-Data-Analysis
Hotel Booking Demand
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.


Objective


We are provided with a hotel bookings dataset.
Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

We have tried to answer the following Questions
1.	Type of Hotels
2.	Type of customer
3.	The number of customers arrived in given years
4.	Which is the busiest month for hotel?
5.	At which date the more customers arrive?
6.	Type of payments customer prefer
7.	How Long People Stay in the hotel?
8.	The most booked Room type by the customers
9.	Preferred stay length in each hotel


10.The most common channel for booking hotels


11.Which significant distribution channel has highest cancellation percentage?


12. How many days prior customers book hotel?


After that we made the predictive model to predict whether the booking will be cancelled or not
We will:


•	Analyse the given dataset


•	Cleaning of the data


•	Evaluate the data


•	Data visualisation


Tools and Libraries Used


We have used Python 3 to its following packages:


•	Pandas


•	Matplotlib


•	Seaborn


DATASET


Dataset contains following features:
1.	hotel
2.	is_canceled
3.	lead_time
4.	arrival_date_year
5.	arrival_date_month
6.	arrival_date_week_number
7.	arrival_date_day_of_month
8.	stays_in_weekend_nights
9.	stays_in_week_nights
10.	adults
11.	children
12.	babies
13.	meal
14.	country
15.	market_segment
16.	distribution_channel
17.	is_repeated_guest
18.	previous_cancellations
19.	previous_bookings_not_canceled
20.	reserved_room_type
21.	assigned_room_type
22.	booking_changes
23.	deposit_type
24.	agent
25.	company
26.	days_in_waiting_list
27.	customer_type
28.	adr
29.	required_car_parking_spaces
30.	total_of_special_requests
31.	reservation_status
32.	reservation_status_date


Result


We learned that
1.	City Hotel are more as compared to the Resort Hotel.
2.	Transient type of customers are more as compared to others.
3.	Most number of customer arrived in 2016 followed by year 2017, and 2015 respectively.
4.	August has the maximum number of customer arrival followed by July ans May
5.	January has least number of customer arrival
6.	Most customers arrived at 17th of the month.
7.	Most of the customers don’t deposit any amount before
8.	Most demanded room type is A
9.	Most common stay length is less than 4 days and generally people prefer City hotel for short stay, but for long stays, Resort Hotel is preferred.
10.	TA/TO most common channel for booking hotels
11.	TA/TO has highest booking cancellation %.
12.	Most of the customers book hotels immediately or 1-6 days prior
