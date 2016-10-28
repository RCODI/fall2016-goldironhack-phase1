Readme Introduction

Developer name: Lindun He

This is a guide for My IronHack Application

1. Name of your Application:

    Go Costless

    It's an application helping customers to find the market which costs least(Food and Fuel costs) and show them the tendency of vegetable price with changing of climate so they can decide what date to go to market. 

2. Keywords

    vegetable price, transportation cost, cost tendency

3. Datasets

    Dataets that will be used are listed. However, at this phase not all details of how they will be used are specified.
(More datasets will be added later. Existing datasets maybe modified later.)
    1.Climate Data Online (http://catalog.data.gov/dataset/climate-data-online-cdo)
    2.Local Markets' Dataset
    3.Gasoline Price Data 

4. Brief Description

When we go to market and buy fresh foods, we usually only calculate the foods' cost. However if we can know the total cost and it's tendency, it will bring customer a clear information to decide what date to go to market and what types of vegetable to buy.
So the application has two main sections. The first one is to show customers tendency of vegetable's price. Customers can search for each type of vegetable's price. Due to the price will change with climate's changing seasonly, the section 1 will show the tendency graphs of different years. The second section will calulate both purchase cost and tranportation cost for each market. And customer can choose the market which costs less.

 Structued Description:
 * Map View:
	1. The initialized Map is located at Indiana state or Great Lafayette(if the dataset is too large)
    2. The markets which are near customer's location are marked on the map.
    3. Market name will shown when mouse is moved to a tag.
    4. There is a side bar on the left of the map and it shows the markets' average cost and automatically calculate the gasline fee for each market.

 * Data Visualization:
	1. For each market, application can show the vegetables' monthly prize with changing climate data(temporature, raining level) using line charts.
    2. Using pie chart to show the prize range for the chosen vegetable.
	
 * Interaction Form:
    1. INPUT: Customer enter the normal weight of vegetable he will buy each time he go to the market. Customer also should enter car's fuel economy(such as 3.6L)
    2. OUTPUT#1: Application will calculate the total price for the customer , then sort the markets and show them on the side bar beside the map. Markets' loacations also appear on the map.
    3. OUTPUT#2: After click the market on the sidebar, application shows detail information about the price and price tendency for vegetables' price.
    4. On the vegetable price tendency section, customer can choose the different type of vegetable. Then the line chart shows information for this type of vegetable.


5 Build Case

I'll try to develop this application only use HTML/CSS/Javascript at first. But if there are some technic issues such as too large dataset causing low effeciency and memory over-using, I will add some new technics like node.js to build a server.

My project will be built on Amazon Web Service, EC2, ubuntu 14.01 instance

6 Test Case

I'll develop the project on Safari and then also test on the Chrome.



