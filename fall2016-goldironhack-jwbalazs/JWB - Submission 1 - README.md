Readme Introduction -- Joseph W. Balazs

This is a guide for how to set up your README.md file for your IronHack Application. The file should have following fields:

1. Name of your Application -- AOD (Aggregator of Data)

2. Keywords
You should include at least 3 keywords for your project to identify the features of your project, such as: freshness, price, transportation convenience
Price, Distance, Freshness

3. Description of the datasets and function design
 * [name] [link] [data type] [data columns used] [data amount] Please provide a name+link+basicInfo to each dataset you have used.
 Indianapolis Interstate Mileposts http://data.indy.gov/datasets/8d10cb86efd9493d8bc785d851e21598_0?uiTab=table 
 * [Y] Do you use the primary dataset ”online climate data” from data.gov? 
 * [Y] [List] Are all these datasets from data.gov or data.indy.gov? If not, where are they coming from (links)?


4. Brief Description

 * Use a paragraph to introduce your project.
I will be making a site that aggregates data from various sources.  I will be focused on the Indianapolis area.  I plan to use farmer's markets like
Trader's Point Creamery as well as supermarkets such as Marsh.  I will make use of climate data from the prescribed data set.  I will also use a data set from
Indy.gov regarding Interstate Mile Markers as a secondary data source; this will help with distance.  Distance will be also accounted for by using Google Maps.  

 Fill in the structued description:
 * Map View:
	1. [Y] Basic Map with specific location (your map is located in a meaningful place, city of west lafayette for example)
	2. [Y] Markers for location of markets
	3. [Y] Labels for markets' names
	4. [Y] InfoWindow to show detail information of a market
	5. [N] [describe] Any other cover on the map (for example, cloud cover to show the weather effect)

 * Data Visualization:
	1. [Y] [describe] Use Graph? What is the type? (bar chart, pie chart, radar chart ...) Bar chart
	2. [Y/N] [List] Any interaction available on the graph? List them (enable click on numbers, drag on lines, change time/variables ...) Undecided
	
 * Interaction Form:
	1. [Y/N] [List] Any information output? list them. (text field, text area, label, plain HTML ...)
	2. [Y/N] [List] Any operation option (filters)? List them. (search markets, search vegetables, filter based on price, sort based on convenience ...)
	3. [Y/N] [List] Any information input? List them. (comments, markers, user preference ...)
	4. [Y/N] [List] Interaction with Map? List them. (filter on price will affect map markers, sort on price will affect map markers, ...)
	5. [Y/N] [List] Interaction with data visualization? List them. (filter, sort, set variables ...)

5. Build Case
How can we build and access your project on a Linux/Unix machine if you use external dependencies besides HTML/CSS/Javascript?
List the dependencies you used, such as python, node.js, etc.
List the steps we should follow to build the project.
Your project will be built on Amazon Web Service, EC2, ubuntu 14.01 instance
N/A 

6. Test Case
Which browsers did you test your project on? Chrome, IE, Edge, Safari, or Firefox? Firefox

7. Additional information You Want to Share with Us
E.g. any problems you faced/fixed, where you reached out to for help, etc.