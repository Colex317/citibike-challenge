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


2. **Gender analysis:**
     - How many trips have been recorded (for each month) during the chosen period?
     - What is the average trip duration per user type (customer vs. subscribers)?
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
- West St & Chambers St  
- 1 Ave & E 68 St   
- 12 Ave & W 40 St

**June 2020:**

- 12 Ave & W 40 St
- 1 Ave & E 68 St
- West St & Chambers St   
- W 21 St & 6 Ave 
- Pershing Square North

--------------------------------------------------------------------------------------------------------------------------------------------


<img width="550" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/70f33a92-d0a8-4003-b661-3dfd314379c5">


<img width="950" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/8fc7feef-4574-4ea3-aafb-9666c97340d7">


--------------------------------------------------------------------------------------------------------------------------------------------


***The top stations in the city for ending a journey for the months of January and June 2020 in descending order were:***
   
**January 2020:**
   
- Pershing Square North       
- E 17 St & Broadway
- West St & Chambers St   
- 1 Ave & E 68 St       
- 12 Ave & W 40 St  
 
**June 2020:**
   
- 12 Ave & W 40 St    
- West St & Chambers St    
- 1 Ave & E 68 St     
- E 17 St & Broadway   
- Pershing Square North  

 
 
 --------------------------------------------------------------------------------------------------------------------------------------------


<img width="550" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/ec813926-08f8-4838-a7a4-bba7aaa4e99b">


<img width="950" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/1ac5f0e8-e37a-4592-9ad6-c83b4dca0087">


--------------------------------------------------------------------------------------------------------------------------------------------


## 3. Gender analysis:

**Number of trips recorded during the chosen period (January and June 2020), showing the changes by gender**

As expected, the number of citibike trips tends to be higher in the summer and lower in the winter.
For the winter month of January 2020, there were:

**Female**

- 279,106 recorded citibike trips compared to 586,361 for the summer month of June 2020 


**Male**

- 904,522 recorded citibike trips compared to 1,044,621 for the summer month of June 2020 


**Unknown** (those who did not state their gender)

- 56,968 recorded citibike trips compared to 251,291 for the summer month of June 2020 

--------------------------------------------------------------------------------------------------------------------------------------------
<img width="778" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/055ac1d6-f749-4cf2-a24f-60900f6dacd7">


<img width="677" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/1efc07e7-cdf7-40d1-ab46-a8140fd0d69c">

--------------------------------------------------------------------------------------------------------------------------------------------

**Average trip duration per user type (customer vs. subscribers), showing the changes by gender**

**Female**
The average trip duration for a female customer (24-hour pass or 3-day pass user) is approximately 38.08 minutes, and the average trip duration for female subscribers (annual membership) is 18.48 minutes.


**Male**
The average trip duration for a male customer (24-hour pass or 3-day pass user) is approximately 32.93 minutes, and the average trip duration for male subscribers (annual membership) is 15.26 minutes.


**Unknown**
For those who did not state their gender, the average trip duration for a male customer (24-hour pass or 3-day pass user) is approximately 51.72 minutes, and the average trip duration for male subscribers (annual membership) is 16.54 minutes.


<img width="680" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/dcb9d59c-983b-48f2-a304-0cb9aba42284">

--------------------------------------------------------------------------------------------------------------------------------------------

**Bike-share usage by gender and average trip duration for each gender by user type**

The data shows that more males (62.42 %) use bike-share more regularly than females (27.71%), and 9.87 % did not state their gender. The average trip duration shows that females have longer rides than males.

**Average female ride duration:**
- Customers (24-hour pass or 3-day pass user) - 38.08 minutes
- Subscribers (annual membership) - 18.48 minutes


**Average male ride duration:**
- Customers (24-hour pass or 3-day pass user) - 32.93 minutes
- Subscribers (annual membership)- 15.26 minutes

--------------------------------------------------------------------------------------------------------------------------------------------

<img width="780" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/071e832a-24fa-47cd-a529-5742129e29e1">

--------------------------------------------------------------------------------------------------------------------------------------------

**Typical start time by gender**

We found that trip start times were the same for both genders. Bike usage was lowest between midnight and 5 AM, and the peak bike usage was at the 17th hour (5 PM). 


<img width="751" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/4a82c27d-3c75-42fe-8e73-b249816b1437">

--------------------------------------------------------------------------------------------------------------------------------------------


## References
Citibike (2024). Hudson River Greenway. Retrieved from https://citibikenyc.com/rides/hudson-river-greenway

GeekforGeeks (n.d.). pandas.concat() function in Python. Retrieved from https://www.geeksforgeeks.org/pandas-concat-function-in-python/

Kranish, Clif (2021). Exploring NYC Bike Share Data. Retrieved from https://towardsdatascience.com/exploring-bike-share-data-3e3b2f28760c#:~:text=This%20shows%20the%20most%20frequently,that%20should%20be%20number%20one.




