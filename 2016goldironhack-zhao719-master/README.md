Readme Introduction

This is a guide for how to set up your readme for you IronHack Application

1. Fresh V

2. Keywords

local vegetables, cheap, fresh, convenience

3. Description of the datasets and function design
 * Datasets
Dataets that will be used are listed. However, at this phase not all details of how they will be used are specified.
(More datasets will be added later. Existing datasets maybe modified later.)

a). Climate Data Online (http://www.ncdc.noaa.gov/qclcd/QCLCD)	
It provide the Quality Controlled Local Climatological Data of Indiana from 01/2014 to 08/2016.
We can use the data to figure out whether a specific place can provide the good qulity vegetable.
Columns used: Heating,Cooling,Temperature,Snow/Ice,Sun,Precipitation

b).Climate Data Online (http://catalog.data.gov/dataset/united-states-average-annual-precipitation-1990-1994-direct-download)	
It provide the United States Average Annual Precipitation from 1990 to 2016.
We can use the data to figure out whether a specific time period can provide the good qulity vegetable.
Columns used: Precipitation

c).Farmer's market data (http://catalog.data.gov/dataset/farmer-markets)
It can help us locate the change of the vegetables in the farmer-markets and help us to know which area have the better and cheaper vegetables.

d).Farmer's market data(https://data.cityofchicago.org/Environment-Sustainable-Development/Farmers-Markets-2015/x5xx-pszi)
It can help us locate the change of the vegetables in the farmer-markets and help us to know which area have the better and cheaper vegetables.

 * Map View

a).The initialized Map is located at West Lafayette since all the people around purdue live here.

b).The markets that sell vegetables will be marked in the map like walmart and meijer.

c).The storege of fresh vegetable will be shown in 3 color red(little), yellow(medium), green(much)

d).Click on the pin of the market, you can see the details of the vegetable and the weather.

 * Data Visualization

a).I think I will use some D3 charts like :Choropleth with svg filter and heatmap to show the data of vegetable in the farmer markets.

b). I will also use the Radar Chart to show the weather. You can click on eating,Cooling,Temperature,Snow/Ice,Sun,Precipitation to see the details.

 * Interation Form:

a).Information output: The route and the link of the markets will be provided. You can also click to choose the specific vegetable and get more details.

b).Information input: Vegetables you want, freshness accepted, distance.

c).Interaction with map: I will combine the map with the heatmap of freshness. Click on the markets can show you the most fresh vegetable in this market. Click on the vegetables can show a clock that describe the time limit of one vegetable in that market.

d).Interaction with data visualization: I will give some button on the rightside to show the specfic data visualization.



 * Content

README.txt --This file.
index.html --Web page for the App
style.css --CSS style file with template from Bootstrap
js --A directory contains all the javescript files
image --A directory contains all images used in the website

6. Test Case

I will test my project on chrome.




Work of Zheng Zhao