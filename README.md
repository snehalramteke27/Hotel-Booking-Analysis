#** Hotel-Booking-Analysis**

**Objective**

We are provided with a hotel bookings dataset.

Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

**Dataset**

We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.
- 
Total number of rows in data: 119390
Total number of columns: 32

**We tried to answer following questions**

Which are the months of highest and least occupation?
What is the most popular meal package?
Which is the most reserved room type?
How many bookings changes have been done during the studied period?
How many people have been registered in the hotel?
What is the most common customer type?

**Conclusion**
  1.	City hotels are the most preferred hotel type by guests. We can say the City hotel is the busiest hotel.
2.	In this exercise we see if there are any missing values present or not.
3.	the majority of reservations are for city hotels.
4.	The majority of guests come from western Europe countries.
5.	Here adr(average daily rate) is correlated with no_of_people. It simply indicates that more revenue is generated when the number of people increases.
6.	The number of repeated guests is too low.
7.	Waiting time period for City hotels is high as compared to resort hotels. That means city hotels are much busier than Resort hotels.
8.	The month of highest occupation is august with 11.65% of the reservations. The months of least 
9.	The majority of reservations convert into successful transactions.

10.	Resort hotels have the most repeated guests.


