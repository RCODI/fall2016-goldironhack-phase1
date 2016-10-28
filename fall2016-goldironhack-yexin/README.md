

 Healthfood finder：
 A meshup created for locals to get health food at the low price and good quality.

1. Keywords
 freshness, price, fertilizer use, consumer satisfaction degree

2. datasets and function design
    a. Climate Data Online (http://catalog.data.gov/dataset/climate-data-online-cdo)
      Use this data for the Precipitation, Winds, Daily total sunshine, Maximum temperature, Minimum temperature, Snowfall
    b. Agricultural Marketing Service (https://www.data.gov/food/agricultural-marketing-service/)
      The data including: farmers market locations, directions, operating times, product offerings
    c. Fertilizer Use and Price (http://catalog.data.gov/dataset/fertilizer-use-and-price)
      The data including: fertilizer consumption in the United States by plant nutrient and major selected product, as well as consumption of mixed fertilizers, secondary nutrients, and micronutrients. 
    d. Consumer Complaint Database (http://catalog.data.gov/dataset/consumer-complaint-database)
       The data including: complaints we’ve received about financial products and services
      All datasets used are from data.gov

3. mapview
      This application aims to provide informations to locals to help them quickly find the market according to the fertilizer use and costomer satisifaction degree. 
      Based on the map, people can see all the market available in specific area and when click the label, here shows 4 dimensions people use for compare and pick : price,fertilizer use, costomer compliant history and locations 
      Once click the label of the market, people can see these informations listing on the right side.
      
4. Data Visualization:
      Pie chart will be used to display the information.
      4 critiria demension would display on the top of the screen. When clicking one of the dimensions like price. A ranking of all the markest would shouw by a pop up window.
	
 * Interaction Form:
      Information output: The weblink of the markets will be provided, the score based on the costomer complaint will be provided. The health score based on the fertilizer will be displayed. The weather condition is shown with a realtime picture telling the weather.
      Interaction with map: Click the labels people can check the rankings based on each factor.

5. Build Case
     README.txt --This file.
     index.html --Web page for the App
     style.css --CSS style file with template from Bootstrap
     js --A directory contains all the javescript files
     image --A directory contains all images used in the website

6. Test Case
Chrome,Safari
