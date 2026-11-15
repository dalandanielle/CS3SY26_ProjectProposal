# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
cvbbbc
### Project Title or Name of the Application	: Biyaheng Pisay
### Section			   	      : 9 - Lithium
### Group Members			    : GO, HALILI, LUMBAO
### Date (Proposal Date)  : Nov 13, 2026
fdfhdfhfshsdhfhhtrthdfh
### Project Description:

- Our project is an object-oriented application designed to log and calculate the daily expenses of a passenger across different modes of transporations. Daily commuters, especially in urban areas such as Quezon City, frequently use multiple modes of transportation when going to various places and back. The main class, "Passenger", represents the commuter with attributes such as "name", "wallet_bal", "type" (such as if the commuter is a student, PWD, senior, or working), and "discount", with methods like "setwallet_bal", which is "depositing" or adding money into your wallter, and "getwallet_bal", deducting money from your wallet whenever you commute. Another class named "Transport" acts as a parent class needed  to store attributes "origin", "destination" and "distance", along with an overwritten attribute "passenger". It features a mthod "calc_fare()" to compute the journey prices. In ur application, we initially propose two modes of transportation—namely , trains and jeepneys. The subclass, "Jeepney", inherits from "Transport" and retains attributes like origin, destination and distance, while overriding the "calc_fare()" methods using a base fare for the first 4 kilometers with additional fees for suceeding kilometers.  The second subclass, "Train", also inherits from "Transport", contains the attributes "station1", "station2", "num_stations", and a boolean attribute "beep_card", overriding "calc_fare()" to calculate the price using a base fee with a lower rate per station passed. It is composed of a "Station" class, which has attributes "name" and "rate". 
- <img width="518" height="251" alt="image" src="https://github.com/user-attachments/assets/f6a6f317-b24d-4a6b-972a-832bbd6c9486" />




**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
