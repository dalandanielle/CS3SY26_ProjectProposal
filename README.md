# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
cvbbbc
### Project Title or Name of the Application	: Biyaheng Pisay
### Section			   	      : 9 - Lithium
### Group Members			    : GO, HALILI, LUMBAO
### Date (Proposal Date)  : Nov 13, 2026
fdfhdfhfshsdhfhhtrthdfh
### Project Description:

- 	Our project is an object-oriented application designed to log and calculate the daily expenses of a commuter across different modes of transportations. Daily commuters, especially in urban areas such as Quezon City, frequently use multiple modes of transport when going to various places back and forth, which is why this application would be of great help to keep them organized with their travel expenses, and see what works for them overtime. The main class, "Passenger," represents the commuter, containing attributes such as "name" (the commuter's name,) "wallet_bal" (the amount of money a commuter has,) "type" (if the commuter is a student, PWD, senior, or working,) and "discount," which  mainly depends on the type of commuter. It also contains the methods "setwallet_bal()" (which either "deposits" or adds money into your wallet, or deducts money whenever you pay the commute fare,) and "getwallet_bal()." Another class, named "Transport", stores attributes "origin" (where a commuter comes from,) "destination" (where a commuter needs to go,) "distance" (how far apart the origin and destination is,), and aggregated "passenger," featuring the "calc_fare()" method to compute the journey prices. In our application we propose two modes of transportation—namely, jeepneys and trains. The subclass, "Jeepney," inerits from "Transport" and retains attributes like origin, destination, and distance, as well as overriding the "calc_fare()" method using a base fare for the first 4 kilometers with additional fees for the suceeding kilometers. The second subclass, "Train," also inherits from "Transport," as well as having a "Station" class (having attributes "name" and "rate", which is the set fare for each station passed by.) It contains the attributes "station1," and "station2" (acting as objects of the "Station" class, representing the origin and destination, respectively,) "num_stations" (representing the number of station you need to go through before you get to your destination,) and a boolean attribute "beep_card," and an overwritten method "calc_fare()", using a base fee with an additional per station passed.The program should be able to display the calculated fare per ride, with any applicable commuter discounts applied. Additionally , the passenger's wallet balance must be updated.
- <img width="501" height="247" alt="image" src="https://github.com/user-attachments/assets/97b65358-0bff-4884-8d41-e458d7a2422d" />



### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
