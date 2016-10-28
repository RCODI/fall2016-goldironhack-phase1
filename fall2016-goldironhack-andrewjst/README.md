
#VegOut -
@Gold Iron Hack 2016   [9/16/16]

A website with a mashup that helps savvy consumers find fresh and cheap vegetables. The application plans to include an interactive timeline that allows those savvy veggie hunters to know the best time of the year for specific veggies. Uses a Google Map API combined with open datatsets from sources such as data.gov. It will have a compilation of data that will include but not limited to freshness, price, transportation conveniance, and veggie time line / sunbursts. The app will place an emphasis on mobile first (responsive) design. Additionally, much of the apps data visualization and main elements will allow interaction.

##Description of the datasets and function design
No datasets have been used yet. However, possible future data sets include Clime Data Online, Data.gov, Data.indy.gov & http://www.ers.usda.gov/

_*Specific Data to be Determined.*_
 * [name] [link] [data type] [data columns used] [data amount] Please provide a name+link+basicInfo to each dataset you have used.
 * [Y/N] Do you use the primary dataset ”online climate data” from data.gov? 
 * [Y/N] [List] Are all these datasets from data.gov? If not, where are they coming from (links)?

 Fill in the structured description:
####Map View
---
- Basic Map with specific location (your map is located in a meaningful place, city of west lafayette for example)
- Markers for location of markets
- Labels for markets' names
- Responsive design that allows the user to select a point and be given the option to use the Google Maps app.


###Data Visualization & Frameworks
---
 [D3.js](https://d3js.org/)
 jQuery
 Bootstrap
 Fresh Guage 
 Graphs: Sunburst, Animated Donut, Bar Charts.
 Interactions: Allows clicking to navigate.
	
 * Interaction Form: (To be determined)
	1. [Y/N] [List] Any information output? list them. (text field, text area, label, plain HTML ...)
	2. [Y/N] [List] Any operation option (filters)? List them. (search markets, search vegetables, filter based on price, sort based on convenience ...)
	3. [Y/N] [List] Any information input? List them. (comments, markers, user preference ...)
	4. [Y/N] [List] Interaction with Map? List them. (filter on price will affect map markers, sort on price will affect map markers, ...)
	5. [Y/N] [List] Interaction with data visualization? List them. (filter, sort, set variables ...)

####Build Case
----
Currently no external dependencies are needed.  All HTML/CSS/Javascript and Data are included with the files. Just download the entire solution and open up index.html

####Test Case
-----
Current frame was built and tested in the latest version of Chrome and Firefox Beta (49.0)

####Content
----
- index.html
- src (main housing resources folder)
    - css
    - fonts
    - js
    - images
    - data

#####Additional information You Want to Share with Us
-------
>Built a small wrapper template.  Includes a sticky top navbar and a collapsible sidebar. The sidebar moves off the side of the page and enlarges the elements in the main frame.


>*Current Application is Under Development*