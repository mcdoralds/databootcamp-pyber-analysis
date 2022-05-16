# PyBer Analysis

## Project Overview:
### Bacgkround
The popular ride share company PyBer would like to take a deeper look into the ride share and driver data collected across 120 different cities. They've provided the raw data and have reached out for assistance in parsing, analysing, and summarzing the key takeaways of the given report.

### Resources
Link to resources provided by client here: 
  - The city_data .csv provides insight on the number of drivers by City. The ride_data .csv has all the ride data, including the city, fare, date of ride, and unique ride ID.
Python 3.7, Anaconda, Jupyter Notebook

## Objectives:
PyBer would like us to compare data points in various ways using the raw data provided in the .csv files. The purpose of this analysis is to uncover trends and identify outliers for further investigation.

The client has specifically requested that the following items be focused on in the analysis:
- A bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
- A method to determine the mean, median, and mode for the following:
  - The total number of rides for each city type.
  - The average fares for each city type.
  - The total number of drivers for each city type.
- Box-and-whisker plots that visualize each of the following to determine if there are any outliers:
  - The number of rides for each city type.
  - The fares for each city type.
  - The number of drivers for each city type.
- Create a pie chart that visualizes each of the following data for each city type:
  - The percent of total fares.
  - The percent of total rides.
  - The percent of total drivers.

## Results:
Direct link to graphs produced from analysis here: 

The following key metrics were calculate and organized into a DataFrame in order to compare ride, driver, and fare data by city type. The following table shows the breakdown between city types:

![image](https://user-images.githubusercontent.com/31219195/168521949-47083805-7f34-457b-8e2c-1aae8af80303.png)

Urban cities had the most rides and total drivers.They also had the highest total fare for the given time period. Urban cities had the lowest average fare per ride and average fare per driver. Overall, urban cities brought PyBer the most revenue, compared to suburban and rural cities.

![Fig8](https://user-images.githubusercontent.com/31219195/168522308-fe2977fd-3367-40fb-9075-a0140a694bdd.png)


### Percentage by city type
The Pyber rideshare program is most used in urban cities, compared to suburban and rural cities. 

As shown below, more than 2/3 of the total rides were from customers calling from urban cities.

![Fig6](https://user-images.githubusercontent.com/31219195/168516693-3b7b6d43-2d70-4290-aaaf-6c4d6f193300.png)

Over 60% of the total fares (in USD $) were from rides within urban cities.

![Fig5](https://user-images.githubusercontent.com/31219195/168516691-dbaccb46-6582-400c-9911-99cfd76c1c20.png)

Interestingly, over 80% of PyBer drivers were from urban cities. 

![Fig7](https://user-images.githubusercontent.com/31219195/168516694-8b6b2ff6-2d42-4bcf-88dc-5468a598125d.png)

At a glance, the three pie chart comparisons may suggest that the relationship between available drivers with total rides and fares, as well as the relationship between rider customer base with total drivers choosing to find employment through driving with PyBer.

### Average fare per ride per driver by city type
The bubble chart below displays the historic relationship between average fare price and the total number of rides per driver, categorized by the three different city types. The size of the circle correlates with the driver count per city. 

![Fig1](https://user-images.githubusercontent.com/31219195/168516628-7ee711e7-cdd9-4848-bf9d-663ee99643d6.png)

The chart shows that urban cities tend to have the highest driver density as well as lowest average prices. Rural cities, which had the lowest number of rides and revenue of all city types and the lowest driver count per city, do appear to have a higher average fare per ride compared to urban and even suburban cities.

### Outliers
Our bubble map above shows a clear trend between average fare, driver density, and total number of rides per city. One thing that may warrant further investigation may be the rural city that managed to keep average fare low, despite having a low driver density and one of the fewes total rides. For example, this may be in part do to new customer promotions and low retention rates. 

![image](https://user-images.githubusercontent.com/31219195/168522633-2e24e279-0603-41fe-9f7f-03c4938b5033.png)

Our scatterplot analysis of the ride counts by city type shows another potential outlier in Urban Cities. PyBer may want to look into the reason for the exceptionally high number of rides for that particular city and perhaps apply those methods to promote its rideshare services in other cities.

![Fig2](https://user-images.githubusercontent.com/31219195/168522817-b37f133d-37c7-4587-b223-0cf70f23c90a.png)

### Key Takeaways
1. Urban cities have the highest total rides and fare, which makes them currently the most profitable regons for PyBer ride sharing and expansion.
2. Trends in rides on a month-to-month basis seem consistent across city types, with ebbs and flows possibly correlating to seasonal activities or events.
3. The availability of drivers (driver density), the total rides, and the total fare all appear to be interconnected. Being in a city where there are more rideshrae customers looking for driving services may attract more drivers. Having a higher driver density may lead to faster service and therefore a higher customer service rating, which would in turn lead to additional new customers. Having more drivers and more rideshare customers leads to lower costs, which further feeds into the customer interest in PyBer's ridesharing services.
