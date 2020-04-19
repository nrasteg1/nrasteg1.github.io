## Exploration of Air Quality in Baltimore City 
**Project description:** I used an inverse-distance weighted interpolation to project the air quality of Baltimore city during December, 2018. I obtained data from all of the outdoor sensors in or near Baltimore city during the month of December, 2018 that could be downloaded from purpleair.com. For each sensor, I calculated an arithmetic mean of all measurements of atmospheric PM 2.5 ug/m3 collected during that period. 
Each sensor came equipped with two different monitors, so I mapped the "A" and "B" sensors seperately. Generally, the maps were very similar, with only +/-2 ug/m3 difference maximum. However, with so few data points these small difference created obvious visual differences in the IDW's shown below. 


<img src="/images/AsensorsFinalMap.png?raw=TRUE"/>
<br>
<img src="/images/BsensorsFinalMap.png?raw=TRUE"/>

Below you will find a map of land use in Baltimore city to compare to my maps of PM 2.5. Keep in mind that the most recent available land use data is from 2010. 

<img src="/images/LULC_Map.png?raw=TRUE"/>

This project was completed using R and QGIS. 

Future steps:
I will create IDW's using the median measurments from the same sensors. 
I will use Average Annual Daily Traffic data to create an interpolation of high-pollution areas to compare to the sensor IDW's. 
