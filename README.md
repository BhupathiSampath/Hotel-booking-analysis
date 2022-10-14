# Hotel-booking-analysis
Exploratory data analysis of hotel bookings

Abstract

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? And what if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?.

Understanding the business data may be a key aspect in every industry. During this project we are going to perform some exploratory data analysis techniques using descriptive statistics and graphical tools to better understand the data and the best time to book hotel rooms and optimal time to stay in a hotel.

About Dataset

We are given a Hotel booking analysis dataset having 32 columns with 119390 records of room bookings over the time from the different places of customers.

Columns description:
    1. Hotel : Hotel(Resort Hotel or City Hotel).
    
    2. Is canceled : Value indicating if the booking was canceled (1) or not (0).
    
    3. Lead time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
    
    4. Arrival date year : Year of arrival date.
    
    5. Arrival date month : Month of arrival date.
    
    6. Arrival date week number : Week number of year for arrival date.
    
    7. Arrival date day of month : Day of arrival date.
    
    8. Stays in weekend nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to remain at the hotel.
    
    9. Stays in week-nights : Number of week-nights (Monday to Friday) the guest stayed or booked to remain at the hotel.
    
    10. Adults : Number of adults.
    
    11. Children : Number of children.
    
    12. Babies : Number of babies.
    
    13. Meal : sort of meal booked. Categories are presented in standard hospitality meal packages.
    
    14. Country : Country of origin.
    
    15. Market segment : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”.
    
    16. channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”.
    
    17. Is repeated guest : Value indicating if the booking name was from a repeated guest (1) or not (0).
    
    18. Previous cancellations : Number of previous bookings that were canceled by the customer before the current booking.
    
    19. Previous bookings not canceled : Number of previous bookings not canceled by the customer before the current booking.
    
    20. Reserved room type : Code of room type reserved. Code is presented rather than designation for anonymity reasons.
    
    21. Assigned room type : Code for the sort of room assigned to the booking.
    
    22. Booking changes : Number of changes/amendments made to the booking from the instant the booking was entered on the PMS until the moment of check-         in or cancellation.
    
    23. Deposit type : Indication on if the customer made a deposit to ensure the booking.
    
    24. Agent : ID of the agency that made the booking.
    
    25. Company : ID of the company/entity that made the booking or liable for paying the booking.
    
    26. Days in roll : Number of days the booking was in the waiting list before it was confirmed to the customer.
    
    27. Customer type : sort of booking, assuming one among four categories.
    
    28. Adr : Average Daily Rate as defined by dividing the sum of all lodging transactions by the entire number of staying nights.
    
    29. Required car parking spaces : Number of car parking spaces required by the customer.
    
    30. Total of special requests : Number of special requests made by the customer (e.g., bed or high floor).
    
    31. Reservation status : Reservation last status, assuming one among three categories.
    
    A. Canceled – booking was canceled by the customer.
    
    B. Check-Out – customer has checked in but already departed.
    
    C. No-Show – customer didn't check-in and did inform the hotel of the reason why.
    
    32. Reservation status date : Date at which the last status was set. This variable are often used in conjunction with the Reservation Status to understand when the booking was canceled or when the customer checked-out of the hotel.
    

Problem Statement

Hotel booking analysis dataset having 32 columns with 119390 records of room bookings over the time from the different places of customers.
This data set contains booking information for a city hotel and a resort hotel and includes information like when the booking was made, length of stay, the amount of adults, children, and/or babies, and therefore the number of available parking spaces, among other things. All personally identifying information has been faraway from the data.
In this project we will explore the data set and analyze the data to discover important factors that govern the bookings.

Introduction

The hotel industry may be a very volatile industry and the bookings depend on various factors such as type of hotels, seasonality, days of week and lots of more factors. This makes analyzing the patterns available within the past data more important to help the better. Using the given historical data, hotels can perform various campaigns to extend the business.

We will try to answer few question mentioned below:

    1. Which hotel type is most preferred by customers?
    
    2. Which type of customers has more bookings?
    
    3. Which type of rooms are most preferred rooms?
    
    4. What is the cancellation of bookings with respect to Distribution Channel?
    
    5. What are the explanations for cancellation of bookings?
    
    6. Which agent made more bookings?
    
    7. What is the percentage of repeated guests?
    
    8. What is the percentage distribution of required car parking spaces?
    
    9. What is the percentage of booking changes made by the customer?
    
    10. Which channel is made more bookings?
    
    11. Which channel is used for early bookings?
    
    12. Which channel making good revenue generating with respect to hotel?
    
    13. What is the adr across the market segments?
    
    14. What is the number of bookings by month wise?
    
    15. What is the adr across the months?
    

Conclision:

    •  City hotels are the most preferred hotels. Thus, City hotels are busiest than Resorts.
    
    •  Transient customer type is more percentage of booking which is 82.4% and Group type is low which is 0.6%.
    
    •  Most of the guests are preferring the rooms "A"(Code of room type). So, Code "A" type rooms can be increased to increase the bookings.
    
    • 27.5% bookings has been cancelled.
    
    • Distribution channel "TA/TO" has more cancellations with 89.13%.
    
    • Less than 150 days waiting list has been canceled and there are no canceled bookings also more in less than 150 days waiting list. Hence, we can         say days in waiting list is not much affecting the cancelation.
    
    • Lead time also not much affecting the cancelation of bookings.
    
    • The same room allotted and not allotted are almost similar. Hence, not getting the same room is affecting the daily "adr". Guests who are not             getting the same room are paying the less adr compared to same room allotted.
    
    • Agent with ID Number: 9 has done more bookings.
    
    • There is only few guest are repeated which is 3.9%.
    
    • 91.6% guests did not require the parking space where only 8.3% of guests required only 1 parking space.
    
    • Distribution channel "TA/TO" has done more bookings and used for early bookings.
    
    • Distribution channels 'Direct' and 'TA/TO' are contributing the most in both types of hotels. GDS distribution channel should focus on increasing         the bookings of 'City Hotel'.
    
    • Market segment "Direct" has the high adr in both Resort and City hotels where "Complementary" has less. Aviation segment can focus on City hotel.
    
    • Bookings have been increasing till the mid of year and we can see in August bookings went to highest. Hence, Most of the people are planning trips       in august month.
    
    • Avg adr rises from beginning of year up to middle of year and reaches peak in August and then lowers to the end of year. But hotels do make some         good deals with high adr at end of year also.
    
    • Mostly bookings are done by couples(although we are not sure that they are couple as data doesn't talk about that).
    
    • It is clear from the graph that there is a sudden surge in the arrival number of couples and families in the months of July and August. So better         plans can be planned accordingly at that time for these types of customers. 
    
