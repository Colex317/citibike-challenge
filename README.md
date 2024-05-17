# Citibike Challenge
## Tableau Exercise

As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program. Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Website](https://citibikenyc.com/system-data). 

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. The selected period was January 2020 (the winter month) and June 2020 (the summer month).

# Files Included
- [Python Script](https://github.com/Colex317/citibike-challenge/blob/main/citibike_data.ipynb)

- [Vizualizations - Tableau Public Workbook](https://public.tableau.com/app/profile/marsha.cole5675/viz/citibike_challenge_17155523190470/CitiBikeStory?publish=yes)


# Questions
In this assignment, the aim was to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena. The chosen phenomena are:
1. **Most popular start and end stations:**
    - What are the top stations in the city for starting a journey (for the months of January and June)? Based on the data, why?
    - What are the top stations in the city for ending a journey (for the months of January and June)? Based on the data, why?

2. **Citibike usage and trip durations:**
   - What is the duration of a bike trip for the top 10 users?
   - How many trips have been recorded in total during the chosen period?
   - What is the average trip duration per user type (customer vs. subscribers)?
   - What is the average trip duration for the months of January and June?

3. **Gender analysis:**
     - What is the average trip for each gender by user type?
     - What is the typical start time by gender?

# Analysis
1. **Most popular start and end stations:**
   

    **Pershing Square North** is among the largest stations in the system. It is located just south of Grand Central Terminal, a significant railroad and subway hub, which explains why it ranks among the top stations.

    The greenway along the Hudson River is a highly popular spot for riding, offering scenic water views and a dedicated bike path free from car traffic. Consequently, the station at **12 Ave & W 40 St** may be popular due to its close proximity to the Hudson River Greenway.

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

   <img width="796" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/99b0a0d1-f0c0-4563-b64d-1ccb698ef1a9">

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
 
    <img width="818" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/18427b35-22d4-4eee-912e-a275787a07c5">


   <img width="980" alt="image" src="https://github.com/Colex317/citibike-challenge/assets/148498483/19ddf3bf-9dd4-4c80-b4e2-a9156a40c21b">


--------------------------------------------------------------------------------------------------------------------------------------------


3. Citibike usage and trip durations:
   - What is the duration of a bike trip for the top 10 users?
   - How many trips have been recorded in total during the chosen period?
   - What is the average trip duration per user type (customer vs. subscribers)?
   - What is the average trip duration for the months of January and June?

4. Gender analysis:
     - What is the average trip for each gender by user type?
     - What is the typical start time by gender?


## References
Citibike (2024). Hudson River Greenway. Retrieved from https://citibikenyc.com/rides/hudson-river-greenway

GeekforGeeks (n.d.). pandas.concat() function in Python. Retrieved from https://www.geeksforgeeks.org/pandas-concat-function-in-python/

Kranish, Clif (2021). Exploring NYC Bike Share Data. Retrieved from https://towardsdatascience.com/exploring-bike-share-data-3e3b2f28760c#:~:text=This%20shows%20the%20most%20frequently,that%20should%20be%20number%20one.




