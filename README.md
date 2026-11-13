# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
cvbbbc
### Project Title or Name of the Application	:
### Section			   	      : 9 - Lithium
### Group Members			    : GO, HALILI, LUMBAO
### Date (Proposal Date)  : Nov 13, 2026
fdfhdfhfshsdhfhhtrthdfh
### Project Description:

- Our project is an object-oriented application designed to log and calculate the daily expenses of a commuter across different modes of transportation. Daily commuters, especially in urban areas such as Quezon City, frequently use multiple modes of transportation when going to various places and back. The class, "transport," acts as the parent class with attributes: "origin," "destination," and "distance." Additionally, it has the following method: "calc_fare()", which calculates the price of the journey. In our application, we initially propose two modes of transportation—namely, trains and jeepneys. The subclass, "train," will have the attributes: "station1," which overwrites origin, "station2," which overwrites destination, and "num_stations," which overwrites distance. It also retains the method: "calc_fare()", however, it is calculated using the base fee with the additional rate of each station. The second subclass, "jeepney," will have the same attributes inherited from parent class "transport." Nonetheless, the method "calc_fare()" is still calculated differently due to a base fare for the first 4 kilometers with additional fees for succeeding kilometers. Given this information, both subclasses "train" and "jeepney" inherit from the parent class "transport," thus exhibiting a hierarchical inheritance system. Depending on the mode of transport, the application uses an object from the train or jeepney class. When the function "calc_fare()" is called, the program is expected to use the attributes, "num_stations" for trains and "origin" and "distance" for jeepneys, as well as the assigned formula for the two subclasses.

**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
