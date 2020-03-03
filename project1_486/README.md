
- What is the topic?
The correlation between lead measurements and PM 2.5 measurements.
- What are the data and where is the data obtained from (provide links too)?
Data is from the EPA, obtained here: https://www.epa.gov/outdoor-air-quality-data/download-daily-data, and gives day-by-day PM 2.5 measures and 3-day lead pollution measurements for all monitors by state. I will download the data for 1 state in 2019. 
- Are there any necessary transformations or subsets you need to do to the data?
I will need to join the datasets based on time/date of data collection and/or average the pm 2.5 over a three day period 
- What is the analysis you'll be performing on your data sets?
I will be doing nearest neighbor and then running statistics to see what the correlation is between the PM 2.5 and Lead values at each nearest neighbor, overall. 
- What outputs will you be creating and how are they directly connected to the class?
I will be creating a web map with the monitoring stations, the major roads, the metal TRI sites, and the nearest neighbor lines as shown in the QGIS book. Average lead and PM 2.5 values of each monitor over 2019 will be attached as popups on each.  
