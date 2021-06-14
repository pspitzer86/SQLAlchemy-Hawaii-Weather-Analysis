# SQLAlchemy-Hawaii-Weather-Analysis

Connecting SQLAlchemy and Python databases, weather data at various weather stations in Hawaii were queried out, analyzed, and graphed to view the projected precipitation and temperature patterns for a potential vacation to Hawaii.  First, the precipitation data was queried and analyzed.  The most recent date in the data was found, the date for one year prior was calculated and all precipitation data within that year was queried and plotted to find potential patterns.  A query was then used to find the most active station within the data.  From the most active station, the min, max and avg temperature measured was found.  The temperatures were then plotted in a histogram to see the frequency of temperatures within the same year range used for the precipitation analysis.  An application was then made for a webpage with paths to JSONS of the precipitation data, station data, temperature data within the year range, and the min, max, and avg temperatures within a range of a date entered by the user and the most recent date, as well as within a start and end date provided by the user.  Additionally, the temperature data was analyzed in two different ways.  First, the avg temperature in June and December where queried out and compared using a T-test to see if there was a significant difference between the two months.  The t-test revealed that there indeed was a significant difference between the means of temperature between June and December.  Second, the min, max, and avg temperature for a planned vacation trip from Aug 1st to August 7th were calculated using a premade method, which was then plotted as a bar plot of the avg temperature and an error bar made from the max and min temperatures.  The final part of the part used a premade method to calculate the average rainfall between the date range for the vacation trip from each of the weather stations in order to see the likelihood of rain during the trip.


![image](https://user-images.githubusercontent.com/65049133/121839370-b9d37f00-cc8e-11eb-9e63-024d4356ab46.png)
