Readme Introduction

This is a guide for how to set up your readme for you IronHack Application

1. Name of your Application

V Need

2. Keywords
You should include at least 3 keywords for your project to identify the features of your project, such as: freshness, price, transportation convenience

Fresh, Fast, Fair

3. Description of the datasets and function design
 * [name] [link] [data type] [data columns used] [data amount] Please provide a name+link+basicInfo to each dataset you have used.

The dataset to be used other than climate data on data.gov is not decided yet.

 * [Y/N] Do you use the primary dataset ”online climate data” from data.gov? 

Yes.

 * [Y/N] [List] Are all these datasets from data.gov? If not, where are they coming from (links)?

No. Not all of the datasets are from data.gov. Probably from web crawler. The other datasets to be used is still not clear.

4. Brief Description

 * Use a paragraph to introduce your project.

The app is called ‘V need’. V stands for the initial letter of the word ‘vegetable’ as well as a similar pronunciation of ‘We’. This pun appeal for both the need to acquire vegetable (Vegetable needs) and the information that the user care about the best location to acquire vegetable (We need it to be…). By decomposing the important factors in making decision to buy vegetables, the three factors, fresh (as no bad weathers in previous days), fast (as shortest distance from the user), and fair (as budget prices) are focused.


 Fill in the structued description:
 * Map View:
	1. [Y] Basic Map with specific location (Chicago)
	2. [Y] Markers for location of markets
	3. [Y] Labels for markets' names
	4. [N] InfoWindow to show detail information of a market
	5. [N] [describe] Any other cover on the map (for example, cloud cover to show the weather effect)

 * Data Visualization:
	1. [Y/N] [describe] Use Graph? What is the type? (bar chart, pie chart, radar chart ...)

Yes. Using radar graph to indicate the freshness/distance/price of a certain supermarket for a selected vegetable.

	2. [Y/N] [List] Any interaction available on the graph? List them (enable click on numbers, drag on lines, change time/variables ...)

Yes. Click on the radar graph mentioned above to enlarge the graph with detailed overview on freshness/price change graph in the previous few days.

	
 * Interaction Form:
	1. [Y/N] [List] Any information output? list them. (text field, text area, label, plain HTML ...)

Yes. The output will be a list with name of the market, corresponding price, distance from the user, and others in the form of text.

	2. [Y/N] [List] Any operation option (filters)? List them. (search markets, search vegetables, filter based on price, sort based on convenience ...)

Yes. The search output will be a list sorted by one of the selected criteria about freshness/distance/price. Filters on vegetables, market will be available.

	3. [Y/N] [List] Any information input? List them. (comments, markers, user preference ...)

Yes. Additional filter may be applied in searching for the result in the form of text input.

	4. [Y/N] [List] Interaction with Map? List them. (filter on price will affect map markers, sort on price will affect map markers, ...)

Yes. Sorting on freshness/distance/price or other user search filters will affect map markers, displaying only top 5-7 on the output list.

	5. [Y/N] [List] Interaction with data visualization? List them. (filter, sort, set variables ...)

Yes. As mentioned in the ‘Data Visualization’ in ‘4. Brief Description’, the freshness/distance/price radar graph will be showing on the map near the supermarket markers. The graph can be enlarged to see detailed information such as historical trend.


5. Build Case
How can we build and access your project on a Linux/Unix machine if you use external dependencies besides HTML/CSS/Javascript?
List the dependencies you used, such as python, node.js, etc.
List the steps we should follow to build the project.
Your project will be built on Amazon Web Service, EC2, ubuntu 14.01 instance

Currently no plan of using other dependencies and server side implementation.


6. Test Case
Which browsers did you test your project on? Chrome, IE, Edge, Safari, or Firefox?

Preferably in Chrome, Firefox for the secondary choice.


7. Additional information You Want to Share with Us
E.g. any problems you faced/fixed, where you reached out to for help, etc.

Currently do not know where to find a place providing vegetable prices neither have the knowledge to create a web crawler to successfully fetch prices from various supermarket websites.

\ No newline at end of file