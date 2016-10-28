
1. “I want my vegetables to be cheap and fresh” v1.0.0    2016-09-16

This is a website with a mashup that combines local farmer’s markets data along with weather and seasonal data. The goals of designing this website is to help the people who live in in West Lafayette/Lafayette and in the Greater Lafayette Area  getting the cheapest and best local products from markets .

2. Keywords
   freshness, price, interaction

3. Description of the datasets and function design
   
   Dataets that will be used are listed. However, at this phase not all details of how they will be used are specified.
(More datasets will be added later. Existing datasets maybe modified later.)

  a.Climate Data Online (http://catalog.data.gov/dataset/climate-data-online-cdo)
    Normals Daily Data for Lafayette from 9/16/2012 to 9/16/2016
    Columns used: Precipitation, Winds, Maximum temperature, Minimum temperature, Snowfall
  
  b.Price Spreads from Farm to Consumer(http://catalog.data.gov/dataset/price-spreads-from-farm-to-consumer)
    USDA Economic Research Service (ERS) compares prices paid by consumers for food with prices received by farmers for corresponding commodities. This data set reports these comparisons for a variety of foods sold through retail food stores such as supermarkets and super centers. Comparisons are made for individual foods and groupings of individual foods-market baskets-that represent what a typical U.S. household buys at retail in a year.
    Columns used: Dairy (Milk and dairy Butter,Whole milk,etc.) Fresh fruit(apples,grapefruits,lemons,oranges,etc.) Fresh vegetables(broccoli,lettuce,etc).

  c.SNAP Retail Locator(http://catalog.data.gov/dataset/snap-retail-locator#topic=food_navigation)
    The datasets is intended to offer assistance to program recipients, State eligibility workers, community organizations - such as food banks - and others providing assistance to those in need. SNAP Retail data will make it easier for SNAP participants, especially those who may be new and unfamiliar with the program, to gain access to food. 
    
4. Brief Description

 * This website is to help people find and compare the cheaper and fresher food resource. Both the function and the interface is user-frendly.

 Fill in the structued description:
 * Map View:
	1. The initialized Map is located at the Greater Lafayette.
	2. The map which shows all the locations of food recource is placed on the left side of the website.
	3. locations of the food recource will be marked on the map with tags .
	4. Market name will shown when mouse is moved to a tag, and when users click on a tag, information for the location will be shown on the webpage. Information contains the features discussed above for a market
	5. Current weather data will be retrived use OpenWeatherMap API (http://openweathermap.org/api), and be displayed in the information windown with a weather icon at the webpage.

 * Data Visualization:
	1. The amount of stars indicates how good or bad of products in the market.
	2. Comparison button will be displayed on the information window. By clicking it, a pop up window that allows the comparison of several markets will be displayed. radar charts is used for the comparison for the markets
	3.By clicking on some features (i.e. price) will display the actualy price range on the chart

 * Interaction Form:
        
	1. Information output: weblink ,address and market Status will be provided to the users. and user could see other users feedback or rate.
	2. Operation options:Filters based on features will affect the change of tags on the map, and search on market names will only result to the tags of a certain set of markets (e.g. search "Walmart" will only display tags for Walmart)
	3. Information input: Allow user leave comments or rate those markets.
	4. Interaction with Map: User could click the map to add the market to the comparsion list.
	5. Interaction with data visualization : user could chose one of the dimension of data such as: distance, price, service. And then they will be provided a ranking of the chosen markert.

5. Build Case
At this point the project only uses HTML/CSS/Javascript. However, other dependencies might be used in the future. An updated readme file will then be submitted along with later submissions.

6. Test Case
The complete version of this App is exptected to be tested on the following broswers: Chrome, IE, Edge, Safari, or Firefox?

7. Additional information You Want to Share with Us
At this moments , Find the data of the farmer market in great Lafayette area is diffcult.
