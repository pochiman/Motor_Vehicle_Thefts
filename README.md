# Motor Vehicle Thefts

## The Situation
You've just been hired as a Data Analyst for the New Zealand police department to help raise awareness about motor vehicle thefts.

## The Assignment
The police department plans to release a public service announcement to encourage citizens to be aware of thefts and stay safe.
You've been asked to dig into the stolen vehicles database to find details on when, which and where vehciles are most likely to be stolen.

## The Objectives
1. Identify when vehicles are likely to be stolen
2. Identify which vehicles are likely to be stolen
3. Identify where vehicles are likely to be stolen

## The Data Set

#### Motor Vehicle Thefts
Stolen vehicle data from the New Zealand police department's vehicle of interest database containing 6 months of data. Each record represents a single stolen vehicle, with data on vehicle type, make, year, color, date stolen and region stolen.

#### Recommended Analysis
What day of the week are vehicles most often and least often stolen?

What types of vehicles are most often and least often stolen? Does this vary by region?

What is the average age of the vehicles that are stolen? Does this vary based on the vehicle type?

Which regions have the most and least number of stolen vehicles? What are the characteristics of the regions?

#### Objective 1: Identify when vehicles are likely to be stolen
Your first objective is to explore the vehicle and date fields in the stolen_vehicles table to identify when vehicles tend to be stolen.

* Find the number of vehicles stolen each year.
* Find the number of vehicles stolen each month.
* Find the number of vehicles stolen each day of the week.
* Replace the numeric day of week values with the full name of each day of the week (Sunday, Monday, Tuesday, etc.)
* Create a bar chart that shows the number of vehicles stolen on each day of the week.

#### Objective 2: Identify which vehicles are likely to be stolen
Your second objective is to explore the vehicle type, age, luxury vs standard and color fields in the stolen_vehicles table to identify which vehicles are most likely to be stolen.

* Find the vehicle types that are most often and least often stolen.
* For each vehicle type, find the average age of the cars that are stolen.
* For each vehicle type, find the percent of vehicles stolen that are luxury versus standard.
* Create a table where the rows represent the top 10 vehicle types, the columns represent the top 7 vehicle colors (plus 1 column for all other colors) and the values are the number of vehicles stolen.
* Create a heat map of the table comparing the vehicle types and colors.

#### Objective 3: Identify where vehicles are likely to be stolen
Your third objective is to explore the population and density statistics in the regions table to identify where vehicles are getting stolen, and visualize the results using a scatter plot and map.

* Find the number of vehicles that were stolen in each region.
* Combine the previous output with the population and density statistics for each region.
* Do the types of vehicles stolen in the three most dense regions differ from the three least dense regions?
* Create a scatter plot of population versus density, and change the size of the points based on the number of vehicles stolen in each region.
* Create a map of the regions and color the regions based on the number of stolen vehicles.

#### [Project Link]()