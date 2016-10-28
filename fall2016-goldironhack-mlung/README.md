Food Oasis
==========

 - **Project Title**: Food Oasis
 - **Keywords**: Price, availability, local, freshness, poverty-aware
 - **Data Sets**
	 - **Food Access Research Atlas**: http://ers.usda.gov/data/fooddesert Map. fa_access, fa_local, snap_benefits, snap_participation_poverty, snap_participation. Good for information on food availability and the poverty/food stamp use in an area. Measures 70,000 tracts of land.
	 - **Food Price Outlook**: http://ers.usda.gov/data-products/food-price-outlook.aspx Data set. Measures changes in food prices and predicts change to come. Not sure of columns used at this point: too many to narrow down, however: it will be useful to suggest whether or not a food is a good price this season.
	 - **Fruit Tree and Nut Data**: http://ers.usda.gov/data-products/fruit-and-tree-nut-data.aspx Data set. Measures production of fresh and processed fruits and nuts. Can be used to determine average prices and figure out which fruits tend to be local vs imported.
	 - **Fruit and Vegetable Prices**: http://ers.usda.gov/data-products/fruit-and-vegetable-prices.aspx Data set. Estimated prices for 156 fruits and vegetables. To be used in order to pinpoint price ranges and highlight deals (see also Fruit Tree and Nut Data)
	 - **Vegetables and Pulses Data**: http://ers.usda.gov/data-products/vegetables-and-pulses-data.aspx Data set. Virtually identical in scope to Fruit Tree and Nut Data above. Identical in its use within Food Oasis.
	 - **Adoption of Genetically Engineered Crops in the US**: http://ers.usda.gov/data-products/adoption-of-genetically-engineered-crops-in-the-us.aspx Data set. Not sure of its inclusion, but a potential feature would be showing users information on whether or not a crop is GMO.
	 - **Farmer's Markets Directory and Geographic Data**: https://catalog.data.gov/dataset/farmers-markets-geographic-data Data set. Useful for the location of a farmer's market, especially in conjunction with Google Maps.
	 - **Online Climate Data**: https://www.ncdc.noaa.gov/cdo-web/datasets Data set. Using columns that show the weather for the past growing season in comparison to averages, and the amount of precipitation.
 - These data sets are available on USDA.gov, Data.gov, and sometimes on both sites.

**Project Description**
A web site that displays similarly on phones and in browser. Displays a map of the user's area based on their IP address location and their location settings, if shared - also allows the user to enter a location to view fruit/vegetable information for an arbitrary area. 

It will contain map markers for known farmer's markets and for locations recognized by Google Maps API as grocery stores. 

On user tap (mobile) or cursor hover (desktop), a pop-up informational window will appear over a store or over a region (when zoomed out past a certain threshold). This window will include illustrated information with the top 3 most cost-effective fruits/vegetables and the top 3 freshest fruits/vegetables based on computations from the data sets listed above, as well as whether or not a location accepts SNAP benefits. Icons will denote any non-SNAP-eligible foods in the "top" listing. Clicking on a store or market will open a new page with detailed information on that location.
Hovering over a region will display information in a similar information box: top 3 cheapest/freshest fruits and vegetables in the area, and the top food resource in the area based on a combined calculated value involving freshness, price, SNAP acceptance, and reviews on sites like Google Maps and Yelp.

Display of fruits and vegetables will be capable of refinement through drop-down menus and checkboxes including options like "show only fruit", "show only vegetables", and "show only SNAP-accepting locations". This refinement will dynamically affect the display on the map.

A major concern with this current design plan is accessibility. A map-based application, while attractive and usable by the general public, isn't a viable option for people with visual disabilities. This design will require further refinement to ensure that it's accessible to the people who need it, regardless of disabled status. 
On a similar note, it will be important to ensure that the phrasing and iconography of the design are easy to understand without reading in order to accommodate non-native English speakers and the illiterate. 

If time permits, I would want to add features like a nutrition encyclopedia (there are tools for this purpose available on Data.Gov, but they lack a clear API). 
My ultimate goal for this program is to produce an application that improves nutritional literacy and consumer literacy among people who are at an economic disadvantage.

I intend to produce my project using node.js.