# transport-demand-prediction

# Description of the Transport Data
This is a dataset prepared on the demand of transport which has more than 50000 data in which we have to predict how many seats MobiTicket can sell in each ride. This dataset contains 14 different routes going to the same location Nairobi with different timings and routes.

The journey from these 14 origin points to the first stop on the outskirts of Nairobi takes approximately 8 to 9 hours from the time of departure. From the first stop on the outskirts of Nairobi to the main bus terminal, where most passengers disembark, in the Central Business District, it takes 2 to 3 hours, depending on traffic. The three stops each of these routes make in Nairobi (in order) are:

Kawangware: First stop on the outskirts of Nairobi
Westlands
Afya Centre: The main bus terminal where most passengers disembark
Passengers on these bus (or shuttle) rides are not only affected by Nairobi traffic during their journey in the city, but from there they must continue their journey to their final destination in Nairobi, wherever that may be. The traffic may act as a deterrent for those who have the option to avoid buses arriving in Nairobi during peak traffic hours. On the other hand, traffic can be an indication of people's movement patterns, reflecting business hours, cultural events, political events, and holidays.

# Problem Statement
This transport data departs from 14 origin points to the first stop on the outskirts of Nairobi, taking approximately 8 to 9 hours. It contains data of more than 50000. In which we have to estimate how many seats MobiTicket can sell in each ride. It consists of 14 different routes leading to the same location Nairobi with different timings and routes.

What did you know about your dataset?
Answer Here

This dataset is a dataset of demand for a transport which has 51645 rows and 10 columns. In which there is no duplicate value nor any missing value.

# Variables Description
Answer Here

ride_id: unique ID of a vehicle on a specific route on a specific day and time

seat number: seat assigned to ticket

payment method: method used by customer to purchase ticket from Mobiticket (cash or Mpesa)

payment receipt: unique id number for ticket purchased from Mobiticket

travel_date: date of ride departure. (MM/DD/YYYY)

travel time: scheduled departure time of ride. Rides generally depart on time. (hh:mm)

travel from: town from which ride originated

travel to: destination of ride. All rides are to Nairobi.

car_type: vehicle type (shuttle or bus)

max_capacity: number of seats on the vehicle
