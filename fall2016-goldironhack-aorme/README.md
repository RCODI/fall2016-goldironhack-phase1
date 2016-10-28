Readme Introduction

This is a guide for how to set up your readme for you IronHack Application

1. Find My Food

2. Keywords
Freshness, Price, Location

3. Description of the datasets and function design
 I plan to use the U.S. Hourly Preciptiation Dataset from NOAA https://gis.ncdc.noaa.gov/geoportal/catalog/search/resource/details.page?id=gov.noaa.ncdc:C00313. The data has several formats and I have not decided which format I will be using. I plan to find data about precipitation levels throughout the year and compare those to optimal precipitation levels for different kind of produce. Using this information I hope to be able to predict the quality levels of certain types of produce. I also plan to use National Farmers Market Directory https://catalog.data.gov/dataset/national-farmers-market-directory in to find the dates and locations of local farmers markets as well as the types of goods being sold at the markets.

Do you use the primary dataset ”online climate data” from data.gov? Y

4. Brief Description

 I plan to make an online commuinity based around my web application. The application will have a landing page displaying which types of produce are in season right now and have a scaling factor based on precipitation to show the expected quality of each type of vegatable currently. The user can then click a button to show farmers markets in their area. The user can then select a market of their choice. Users will have the option to review a farmers market as well as report how much they paid for products they bought. The app will use this data to display the pricing scale for that farmers market and compare the price for each type of produce to the predicted quality to help the user weigh if they should purchase produce at that market.

 Fill in the structued description:
 * Map View:
	Currently I plan to use a list view to display each farmers market along with the produce offered at the market, price scale, and quality scale. I plan to have a map beneath the list showing the location of all markets on the list using markets. 

 * Data Visualization:
	I plan to have a chart comparing the ratio of price to expected quality of produce at a market to the the average of all markets.
	
 * Interaction Form:
	User will be able to input prices of produce to get an estimate of expected quality vs price. Users will also be able to leave reviews on a market as well as the price they paid for an item at the market. 

5. Build Case
How can we build and access your project on a Linux/Unix machine if you use external dependencies besides HTML/CSS/Javascript?
List the dependencies you used, such as python, node.js, etc.
List the steps we should follow to build the project.
Your project will be built on Amazon Web Service, EC2, ubuntu 14.01 instance

6. Test Case
I Plan to test in Chrome

7. Additional information You Want to Share with Us
None
