# NYC Citibike Analysis

# Overview

We are planning on starting a bike sharing business in Des Moines, Iowa. By using Tableau Public to visualize NYC Citi Bike data from August 2019, we will present our findings to potential investors. We are using the data from August 2019 because there is likely more traffic during the summer months. The more data points we have, the more accurate our results will become. 

Below are some of the questions we are seeking to answer with our data visualizations:
* What is the total number of rides for Citi Bike data from August 2019?
* How long bikes are checked out for all riders and genders?
* How many trips are taken by the hour for each day of the week, for all riders and genders?
* A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender?
* Locations where bikes are checked out and returned? 


## Process:

### Deliverable 1 - Deliverable 1: Change Trip Duration to a Datetime Format
* Convert 201908-citibike-tripdata.csv data to a DataFrame
* Change the 'tripduration' column to datetime datatype
* Export the corrected DataFrame to a new .csv file

### Deliverable 2 - Create Visualizations for the Trip Analysis
* Create [line chart visualization](https://github.com/corispade/bikesharing/blob/main/Images/Checkout_Times_for_Users.png) to graph the length of time bikes are checked out for all riders.
* Create [line chart visualization](https://github.com/corispade/bikesharing/blob/main/Images/Checkout_Times_by_Gender.png) to graph the length of time bikes are checked out by gender
* Create [heat map visualization](https://github.com/corispade/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour.png) to graph the number of bike trips by weekday for each hour of the day
* Create [heat map visualization](https://github.com/corispade/bikesharing/blob/main/Images/Trips_by_Gender.png) to graph the number of bike trips by gender by weekday for each hour of the day
* Create [heat map visualization](https://github.com/corispade/bikesharing/blob/main/Images/User_Trips_by_Gender_by_Weekday.png) to graph the number of bike trips by gender by weekday 

### Deliverable 3 - Create a Story and Report for the Final Presentation
* Created a story to present charts for the following. See results below:
  * Customer Information
  * Trips by Gender
  * Peak Hours

## Resources:
Data Source: [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/index.html)

Software: Python 3.7.6, Conda 4.10.1, Tableau Public 2021.3

Environment: Jupyter Notebook, Tableau Public

Dependencies: Pandas


# Results:
Click [here](https://public.tableau.com/app/profile/cori.spade/viz/CitiBikeAnalysis-Story_16314894698490/CitiBikeData?publish=yes) to access the dashboard. 

### Customer Information
![image](https://github.com/corispade/bikesharing/blob/main/Images/Customer_Info.png)

* There were 2,344,224 total rides in August 2019
* Approximately 81% of rides were subscribers
* Approximately 65% of rides were male, and 25% were female, leaving the remaining unknown
* Based on the map image, the majority of rides ended in areas of business and tourism
* The majority of the trip durations were under 1 hour

### Peak Hours
![image](https://github.com/corispade/bikesharing/blob/main/Images/Peak_Hours.png)

* During the month of August 2019, peak riding hours were from 7-9am and 4-7pm
* Monday to Friday peak hours were 7-9am and 4-7pm
* Saturday and Sunday peak hours were 11am-4pm
* Based on all charts, the best time for bike maintenance is 12am-5am

### Trips by Gender
![image](https://github.com/corispade/bikesharing/blob/main/Images/Gender_Data.png)

* In all images, you can see clearly there are more male than female riders
* Both genders genders both males and females have similar riding habits and peak hours


# Summary:
Based on the findings from NYC Citi Bike data from August 2019, the majority of the rides are in Manhattan during the peak hours of 7-9am and 4-7pm. The majority of riders are male. 

### Further Investigation: 
1. Look into data from other months. We need to be sure that this business is sustainable for the majority of the year. 
2. Look into data from Des Moines. Where are the majority of the businesses? Where do potential customers live? How far are the customers willing to bike? 