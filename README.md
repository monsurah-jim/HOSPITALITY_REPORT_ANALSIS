# HOSPITALITY_REPORT_ANALSIS

# AIMS AND OBJECTIVES
1. Customer Satisfaction: Evaluate and understand customer feedback and preferences to enhance the overall experience.

2.Operational Efficiency: Identify areas for improvement in service delivery, resource allocation, and staff management to streamline operations.

3.Demand Forecasting: Analyze historical data to predict future demand, helping in optimizing inventory and staffing levels.

4.Revenue Management: Optimize pricing strategies based on factors like seasonality, events, and customer behavior to maximize revenue.

5.Personalization: Utilize data to offer personalized services and recommendations, enhancing customer engagement and loyalty.

6.Quality Control: Monitor and maintain service quality by analyzing various performance metrics.

7.Marketing Strategies: Develop targeted marketing campaigns based on customer behavior and preferences.

8.Risk Management: Identify and mitigate potential risks in areas such as security, health, and safety.

# DATA SOURCE
It was an uncleaned data sourced from kaggle. It a dataset that talked about hospitality department

# DATA CLEANING AND PREPARATION
I cleaned the data using excel, created another columns,saved as a csv file and imported into mysql.

# BRIEF EXPLANATION OF THE COLUMNS
It contained 16 colums and 98555 rows and they include

1. Average room rate :The average room at which the room is been rented.
 
2.  Reservation id: The means of identification given to each person staying at the hotel
 
3. Check in date:The date which they checked in the hotel
 
4. Check in month: The month when they checked in the hotel
 
5. Stay duration:How many days they spent at the hotel.
 
6. Adult:How adults stayed in the hotel
 
7. Children:How children stayed in the hotel
  
8. Room type: The type of room they lodge in the hotel
 
9. Special request flag:When special requests are been made to the receptionist
 
10. Booking channel:How the booking was made either on website,walk_in,call_center or travel_agent
     
11. Reservation status: The status of the booking whether it was completed, not completed,no show
 
12. Advanced booking: Whether the booking were made in advanced or in person

13. Property: The property of the person staying the hotel
 
14. Date: The date they checked out of the hotel.
    
15. Month:The month which the reservation is made
    
16. Rate type:Is when the booking is made either on weekday or weekend.

# RESULT OF THE ANALYSIS

# ROOM ALAYSIS

# 1) What is the average room rate per month?
<img width="481" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/c5ff0485-7468-49f2-acdf-d38135d596e9">

# 2) Which property has the highest and lowest average room rates?
## The sankey  suite has the highest room rate
<img width="478" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/5e536a3d-f6ba-4d14-8293-be387096dcf5">

## The sankey double room has the lowest room rate
<img width="494" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/bc650db3-3d23-4135-a65b-12933541185f">

# 3) How do the room rates vary between weekdays and weekends?
## The room rate varies from single,double,to king and queen
<img width="513" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/32a48384-137b-43dc-9b6f-8e300043c2f3">

# RESERVATION AND CHECK_IN ANALYSIS
# 1) What is the average duration of stay based on the room type and property?
## The property,average duration and property varies from each other
<img width="545" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/6a10ad4a-a572-4828-ad64-8f28cd4edc37">

# 2) Is there a correlation between the number of adults/children and the room type?
## The room type, adult and children ranging from single to double to king size, executive suite
<img width="499" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/d0cbcab3-4d2a-4baf-910a-d99a41e99a2a">

# 3) How does the check-in pattern differ across various booking channels?
## The booking pattern in different from across all booking channel but phone app has the highest booking rate
<img width="478" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/349054aa-a2bc-4a9e-b949-e344cfad2a9e">

# 4) What is the total resrvation made, and how many reservation were made by children?
## The total reservation made is 98569
<img width="417" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/257c958f-267d-436d-8af1-5304bb90c349">

# 5) Which reservation has the highest number of children and what is the reservation status
##  The '779087-Y5-9824-SA', has  '4' children which is the highest
<img width="471" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/d97b38aa-e7ab-420c-b064-c821d2c56724">

# 6) How many reservation were made on weekdays and is there an increase in the number of participant compare to total reservation
## The reservation madeis 70282 
<img width="454" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/2ff5ab88-a144-47b1-9c04-5c17d358df7c">

## Total reservation is 98569
<img width="500" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/a718b475-10a9-4392-8bad-b8e49075bf89">

# 7) Two properties with the most in advanced bookings
## The Sankey is '45411' while 'The Marimekko', '22615'
<img width="460" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/72aea7dc-0b53-41e0-9e1c-b5dba8442598">

# 8) What is the relationship between advanced bookings and reservation_status
## The relationship between advanced booking and reservation_status those that decided to not show,those that completed that transaction,those that it was reduced
<img width="460" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/6078f847-8450-4c23-99b5-76919e36f806">


# SPECIAL REQUESTS AND BOOKING ANALYSIS

# 1) How does the completion status relate to special requests?
## They are related because it shows which booking status has special requests
<img width="536" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/df889248-c722-4343-9382-eb82b24ec86a">

# 2) Which room type or property receives the most special requests?
## The sankey double room received the most special request
<img width="543" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/36a68eae-3b27-48fa-a75e-c1c10d03d8cc">

# 3) Are special requests more common during weekdays or weekends?
## There are special requests on weekday and weekends 
<img width="507" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/b0a1c7e5-7388-4f15-ac48-619d60dd8351">

# PROPERTY AND RATE TYPE ANALYSIS

# 1) Which property has the highest occupancy rate or the most bookings?
## The sankey has the highest occupancy rate
<img width="470" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/32aa19ec-a59c-488a-a32c-cd9834d63a2d">

# 2) Compare the rate types across different properties.
## The weekday and weekend has more rate type
<img width="449" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/fbabc1b3-cc95-4e27-91bd-b4489cf796f7">

# 3) Analyze the advanced booking trends based on the rate type.
## Both weekday and weekend has the same advanced booking
<img width="485" alt="image" src="https://github.com/monsurah-jim/HOSPITALITY_REPORT_ANALSIS/assets/148765480/18b38cd6-0dac-4baf-8198-545664472d28">



 
