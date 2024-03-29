# ETL-Project
This project was meant as a basic ETL using SQL and Python

Flight delay data from 2015 was used from Kaggle here: https://www.kaggle.com/usdot/flight-delays#flights.csv
Three Tables were included:

1) Arlines: included the shortcode and corresponding airline name
2) Airports: included the IATA airport code, full name, address and lat long of airports
3) Flights: Includes flight delay information with delay time, airline shortcode and date details

Workflow was as follows:

Upload excel sheets in SQL Lite Database  
Transform data using SQL Alchemy in Python (performing queries and joins)  
Using the transformed data to Python for further analysis (performing equations on the data in pandas, adding columns etc.)  
Uploading our analysis directly from Python into our SQLite database  
We also exported our transformed tables into MySQL in case the uder prefers using MySQL

![Image of Method](https://github.com/lprymak/ETL---Airport-Airline-Data/blob/master/Process%20diagram.jpg)

