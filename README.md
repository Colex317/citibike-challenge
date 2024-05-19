# Citibike Challenge
## Tableau Exercise

As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program. Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Website](https://citibikenyc.com/system-data). 

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. The selected period for this visualization assignment was January 2020 (the winter month) and June 2020 (the summer month).

# Files Included
- [Python Script](https://github.com/Colex317/citibike-challenge/blob/main/citibike_data.ipynb)

- [Visualizations - Tableau Public Workbook](https://public.tableau.com/app/profile/marsha.cole5675/viz/citibike_challenge_17155523190470/CitiBikeStory?publish=yes)

- CSV files - were too large to be uploaded to GitHub.

# Questions
In this assignment, the aim was to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena. The chosen phenomena are:
1. **Most popular start and end stations:**
    - What are the top stations in the city for starting a journey (for the months of January and June)? Based on the data, why?
    - What are the top stations in the city for ending a journey (for the months of January and June)? Based on the data, why?

2. **Citibike usage and trip durations:**
   - How many trips have been recorded in total during the chosen period?
   - What is the average trip duration for the months of January and June?
   - What is the average trip duration per user type (customer vs. subscribers)?
   - What is the total riding duration for the top 10 users over the selected period?

3. **Gender analysis:**
     - Is there a significant gender disparity in the regular usage of bike-share services?
     - What is the average trip duration for each gender by user type?
     - What is the typical start time by gender?

# Analysis
## 1. Most popular start and end stations:
   
`Pershing Square North` is among the largest stations in the system. It is located just south of Grand Central Terminal, a significant railroad and subway hub, which explains why it ranks among the top stations.

The greenway along the Hudson River is a highly popular spot for riding. It offers scenic water views and a dedicated bike path free from car traffic. Consequently, the station at `12 Ave & W 40 St` may be popular due to its close proximity to the Hudson River Greenway.

   ***The top stations in the city for starting a journey for the months of January and June 2020 in descending order were:***

**January 2020:**

- Pershing Square North
- W 21 St & 6 Ave
- E 17 St & Broadway
- Broadway & 22 St
- E 13 St & Avenue A

**June 2020:**

- 12 Ave & W 40 St
- 1 Ave & E 68 St
- West St & Chambers St   
- Broadway & W 60 St 
- Christopher St & Greenwich St

--------------------------------------------------------------------------------------------------------------------------------------------


   <img width="980" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/455736ba-c5cd-4d2b-9eb8-005e78796ce8">


--------------------------------------------------------------------------------------------------------------------------------------------


***The top stations in the city for ending a journey for the months of January and June 2020 in descending order were:***
   
**January 2020:**
   
- Pershing Square North     
- Broadway & 22 St     
- E 17 St & Broadway     
- W 21 St & 6 Ave     
- Christopher St & Greenwich St

  
**June 2020:**
   
- 12 Ave & W 40 St    
- West St & Chambers St    
- 1 Ave & E 68 St     
- Broadway & W 60 St    
- Christopher St & Greenwich St

 
 
 --------------------------------------------------------------------------------------------------------------------------------------------
 

   <img width="980" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/19ddf3bf-9dd4-4c80-b4e2-a9156a40c21b">


--------------------------------------------------------------------------------------------------------------------------------------------


## 2. Citibike usage and trip durations:

**Trips recorded and the average duration of a trip during the chosen period (January and June 2020)**

For the winter month of January 2020, there were 1,240,596 recorded citibike trips compared to 1,882,273 for the summer month of June 2020. The average duration of a trip during January was approximately 13.08 minutes (784.6 seconds), and 27.32 minutes (1639.1 seconds) during June.  As expected, the number of citibike trips tends to be higher in the summer and lower in the winter, and the duration of the trips is also less during the winter months.

<img width="568" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/db6a68b0-498a-4eab-b7c4-adc9b88e3231">

<img width="640" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/76539e5e-671e-4aa6-9184-19e979808e5b">

--------------------------------------------------------------------------------------------------------------------------------------------

**Average trip duration per user type (customer vs. subscribers)**

The average trip duration for a customer (24-hour pass or 3-day pass user) is approximately 41.67 minutes (2500 seconds), and subscribers' (annual membership) average trip duration lasts 16.2 minutes (972 seconds).

<img width="640" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/699dec28-00ed-40c7-867c-fcd27003b744">

--------------------------------------------------------------------------------------------------------------------------------------------

**Total Riding Duration for the Top 10 Users Over the Selected Period**

The top user rode for 148 hours and 43 minutes (535,410 seconds) over two months (January and June 2020).

<img width="675" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/992d0dac-b245-4c4d-9669-68ef30776157">



## 3. Gender analysis:
**Bike-share usage by gender and average trip duration for each gender by user type**

The data shows that more males (62.42 %) use bikeshare more regularly than females (27.71%), and 9.87 % did not state their gender. The average trip duration shows that females have a longer rides than males.

**Female**
- Customers (24-hour pass or 3-day pass user) - 38.08 minutes (2285 seconds)
- Subscribers (annual membership) - 18.48 minutes (1109 seconds)

**Male**
- Customers (24-hour pass or 3-day pass user) - 32.93 minutes (1976 seconds)
- Subscribers (annual membership)- 15.25 minutes (915 seconds)


<img width="485" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/162eccb6-38e8-4c0c-9a4a-5bfa0cc63d10">


<img width="523" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/dc4b8ff3-0b10-4c43-8f91-490cf28733c7">


--------------------------------------------------------------------------------------------------------------------------------------------


**Typical start time by gender**


## References
Citibike (2024). Hudson River Greenway. Retrieved from https://citibikenyc.com/rides/hudson-river-greenway

GeekforGeeks (n.d.). pandas.concat() function in Python. Retrieved from https://www.geeksforgeeks.org/pandas-concat-function-in-python/

Kranish, Clif (2021). Exploring NYC Bike Share Data. Retrieved from https://towardsdatascience.com/exploring-bike-share-data-3e3b2f28760c#:~:text=This%20shows%20the%20most%20frequently,that%20should%20be%20number%20one.




