# Reinforcement-Learning-for-Flight-Ticket-Pricing-DST-1
## Project Report

![](img.jpg)

## DECLARATION

#### A project report on Reinforcement-Learning-for-Flight-Ticket-Pricing project Successfully submitted By
![Mr. Makarand Anna Rayate.](https://github.com/mak-rayate)

![Mr. Prasad Pawar.](https://github.com/Prasad993)

![Mr. Chakradhar Reddy Yerragudi.](https://github.com/chakradhar123)

![Mr. Mervana Prit Jitendrabhai.](https://github.com/Prit005)

![Ms. Deepika Goel.](https://github.com/goeld9911/)

![Mr. Praneeth Kumar.](https://github.com/praneeth300?tab=repositories)

![Ms. Himadri Chutia.](https://github.com/Himadrichutia)

![Mr. Rudra Kumawat.](https://github.com/Rudra-kumawat-22)


## Problem Statement
#### Can we use Reinforcement Learning to help a customer decide the optimal time to purchase a flight ticket?



## ABSTRACT

Airlines employ complex, secretly-kept algorithms to vary flight ticket prices over time based on several factors,including seat availability,airline capacity, the price of oil, seasonality, etc. At any point in time, a customer looking to purchase a flight ticket has the option to buy or wait (in the hope of the flight price reducing in future).However, since they lack knowledge of these algorithms, customers often default to purchasing a ticket as early as possible rather than trying to optimize their time of purchase.However, vast quantities of data regarding flight ticket prices are available on the Internet. Through this project,we hoped to use this data to help customers make their decisions. We created an airline ticket-buying agent that tries to buy a customer’s flight ticket to optimize for price of purchase.We have selected ![MakeMyTrip](https://www.makemytrip.com/flights/) website to scrap the Indian flights data.

## Data
Below is the small sample of our dataset:

![](Screenshot.png)

#### Data points --> 330939 rows
#### Dataset date range --> April 2021 to May 2021
#### Dataset Attributes:

Price - flight price

departure_time	- flight schedule time

arrival_time - arrival time of flight

Airline	Cabin - There are three type

E - Economy

PE - Premium Economy

B - Business

Dept_city - Departure city

Dept_date - Departure Date	

arrival_city - Arrival city	

stops - Number of stops

duration - Flight duration in minutes

weekday	dept_hours	

Dept_flights_time	

optimal_hours

### ML Framework:

Assume a customer decides to purchase a ticket for a particular flight at time = X 
hours before departure. The optimal time to purchase the ticket t0pt is:
- in the range [X hours before dep., 4 hours before dep.]
- time at which we achieve minimum flight price until departure


