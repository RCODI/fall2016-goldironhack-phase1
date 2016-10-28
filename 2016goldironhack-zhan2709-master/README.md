Readme 
1.	Name of Application：every week vegetable 
2.	Keywords  freshness, price, a comfortable day
3.	Description of the datasets and function design
        http://www.ncdc.noaa.gov/cdo-web/ climate data online   provide climate forecast for the week
        http://catalog.data.gov/dataset/farmers-markets-2015  Farmers Markets – 2015   provide the Farmers Markets’ details
                                                   such as “open time, comment of the survey, the location”

4.	Brief Description
        My project will provide a weather forecast by weeks to users to help them choose a day to buy vegetables.
        Users can rank the market by features such as the price, the distance , the freshness of vegetables…
        And then choose a market they interested in. The detailed information of the market will be shown in
        a column.

	Map View:
     a.	[Y/N] Basic Map with specific location    Yes，West Lafayette
     b.	[Y/N] Markers for location of markets     Yes
     c.	[Y/N] Labels for markets' names           Yes
     d.	[Y/N] InfoWindow to show detail information of a market     Yes
     e.	[Y/N] [describe] Any other cover on the map (for example, cloud cover to show the weather effect)  None

	Data Visualization:
     a.	[Y/N] [describe] Use Graph? What is the type? (bar chart, pie chart, radar chart ...)
        Yes, bar chart and line chart will be used.
     b.	[Y/N] [List] Any interaction available on the graph? List them (enable click on numbers, drag on lines, change time/variables ...)


	Interaction Form:
     a.	[Y/N] [List] Any information output? list them. (text field, text area, label, plain HTML ...)
     Yes, the detailed information about the market
     b.	[Y/N] [List] Any operation option (filters)? List them. (search markets, search vegetables, filter based on price, sort based on convenience ...)
     Yes, rank the market by appointed features, show the top5-10 results.
     [Y/N] [List] Any information input? List them. (comments, markers, user preference ...)
    Yes, user’s preference.
    c.	[Y/N] [List] Interaction with Map? List them. (filter on price will affect map markers, sort on price will affect map markers, ...)
    Once user choose a market from the list, the map will show its location.
    d.	[Y/N] [List] Interaction with data visualization? List them. (filter, sort, set variables ...)
    Once the user change the market, the bar chart will change accordingly.

5.Build Case How can we build and access your project on a Linux/Unix machine if you use external dependencies besides HTML/CSS/Javascript? D3.JS

6.Test Case Which browsers did you test your project on? Chrome, IE, Edge, Safari, or Firefox?
    Both Chrome and IE
