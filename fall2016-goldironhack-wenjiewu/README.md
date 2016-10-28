**Fresh Veggies**

Freshness | Price | Comparison

**Dataset Description**
 * Datasets  
	* Climate Data Online (https://gis.ncdc.noaa.gov/geoportal/catalog/search/resource/details.page?id=gov.noaa.ncdc:C00861)  
	  Normals Daily Data for Chicago within 4 years
	  Columns may be used: Precipitation, Winds, Daily total sunshine, Maximum temperature, Minimum temperature, Snowfall  
	* Nearby Cook County Grocery Store Chains (https://catalog.data.gov/dataset/nearby-cook-county-grocery-store-chains-cc102)  
	  A list of grocery stores which are part of a multi-store chain and are located at or within 1 mile of Chicago's city limits
	  Columns may be used: name, location, kinds of vegetable offered  
	* Nearby Independent Cook County Grocery Stores (https://catalog.data.gov/dataset/nearby-independent-cook-county-grocery-stores-180c9)  
	  A list of independently owned- and operated grocery stores which are located at or within 1 mile of Chicago's city limits
	  Columns may be used: name, location, kinds of vegetable offered  
 * Datasets used are from noaa.gov and data.gov  

**Brief Description**

This is a Web App to help people find fresh and cheap vegetables in Chicago.  

The App uses Google Map API combined with open datasets to display freshness and price of a kind of vegetable in all food stores.
Besides, the app also shows the hictorical price of this veggie, price comperison between stores and whether it is a food in season.

 * Map View:
	*  Map location: Chicago
	*  Map shows the location of markets
	*  Map can show or hide Labels for markets' names
	*  It has infoWindow to show detail information of a market
	*  Map view only cover one side of the website. Another side shows the historical price data and price comparison

 * Data Visualization:
	* We use bar chart to show historical price of vegetables
	* The map is focused on one kind of vegetable at a time. Users can change the kinds in the side bar
	
 * Interaction Form:
	* There is no output
	* Operation included: searching market, searching vegetables, choosing vegetable, choosing market to compare
	* There is no input
	* Map can zoom in, zoom out; The market on the map is clickable(showing details)
	* not sure now about how to interact with data

* Build Case
How can we build and access your project on a Linux/Unix machine if you use external dependencies besides HTML/CSS/Javascript?
List the dependencies you used, such as python, node.js, etc.
List the steps we should follow to build the project.
Your project will be built on Amazon Web Service, EC2, ubuntu 14.01 instance

* Test Case
Which browsers did you test your project on? Chrome, IE, Edge, Safari, or Firefox?

* Additional information You Want to Share with Us
E.g. any problems you faced/fixed, where you reached out to for help, etc.
