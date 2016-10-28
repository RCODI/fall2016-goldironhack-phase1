**Freshest**  v1.0.0 - 2016-09-16

This web application for helping people in Indianna find relatively cheap, fresh and accesible vegetables.  
Keywords: fresh vegetables, price, weather, local produce

**Description**

* Datasets  
Most datasets come from data.gov, some other functions are included as well.  
(More datasets will be added later. Existing datasets maybe modified later.)  
  * Climate Data Online (http://www.ncdc.noaa.gov/cdo-web/datasets)  
  Daily Summaries for Indina From 01/01/2008 to 12/31/2010  
  Columns used: Preciptation, Water, Winds, Maximum temperature, Minimum temperature, Weather type (sunny, snow, rain...etc)

  * Price of Local Vegetables  
  local price of vegetables will be obtained from http://catalog.data.gov/dataset/   
  (Still on process to find a more complete dataset of local price foe vegetables)  
  This dataset will give information of location of market, price for certain vegetables

  * Changes in Food Price Indexes (http://www.ers.usda.gov/data-products/food-price-outlook.aspx)  
  The data shows the price change of food in percentage from 2014 to 2017 (prediction).
  Column used: annual change in year (in percentage)

  * Current Weather (http://www.accuweather.com/en/free-weather-widgets)  
  Get current weather based on user's location and show results.  
  Column used: intergreted system from accuweather

* Map View  
  * Initialized Map View will focus on West Lafayette, as they are our main users for now. (*might modify eventually)
  * Market location will be marked on map. Name and detailed information will expand in tooltip after clicking
  * When move the mouse over a target, the current mark will be highlighted and show name of the market.
  * There would be transparency change or integrated heatmap shown on map based on the climate. User can choose to have effect on/off.(This can be applied to google map or our customized Indiana map)
  * There will be another map specificly for Indiana (customized map). It will be a heatmap on the dashboard with a slidebar that can select different date. Relative information of climate of specific date will change on map. Clicking on specific county will give more climate information of selected time.

* Data Visualization  
  * We will use chart visualization from D3.js. We will create barcharts for comparison of vegetables from different markets. Also we will have a line chart for changes in food price for consumer.  
  * Highcharts.js will be used for customized map of Indiana. We will modify the presentation of the map. It will change based on interaction from user. (e.g.: clicking on specific county will show the climate information or the average vegetable price)


* Interaction Form
  * The interaction of the system will mostly be clicking and showing information.
  * Information input: User need to give keywords on search bar or click on specific marker. Use slidebar will give input of selected year or month.
  * Information output: The marker of each market will give information like weblink, avalable product or freshness evaluation. These will be in a form of charts rather than plain text.
  * Operation option: User can search vegetables or specific market.
  * Interaction with Map: 1. User can zoom in/out on google map, check location of markets, click on highighted marker to see market weblink or avalable products. This can coordinate with other charts on dashboard as well.
  * interaction with data visualization: user can scroll the slidebar of Indiana map to see color changes of heatmap, showing the climate change during certain period. User can also click on specific county to see the average vegetable price.

**Build up Information**  
This project uses HTMl/CSS/Javascript. Other decendencies like python will probably be used as well in terms pf pre-processing data. README file will be updated at different phases with detailed description of the project.

**Test**  
The project will be tested on Chrome.

**Problems**  
Currently I have trouble looking for very detailed dataset of vegetable prices that differ among different markets. Given more detailed geographic data of market along with various vegetables' price, the system design can be more refined.

**Demo picture**
https://github.com/goldironhack/2016goldironhack-ravengao/blob/master/demo-1.jpg
