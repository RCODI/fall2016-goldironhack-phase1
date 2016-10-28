# Best Veggies v1.0.0 - 20160916
The goal of this web application is to help people get the freshest and cheapest vegetables nearby in the easiest way.
The application shows custom results for different users based on their preferences, such as freshness, price, distance, rating, etc.

### Key Words
    fresh, cheap, high-rating, convenience

### Main Functions
* Map view
* Search a certain farmer/supermarket
* Preferences setting
* Details lookup
* Special events
* Favorite farmers/supermarkets, History
* To-buy list

### Description
* Datasets (data.gov)
	- Local farmers: still looking for a suitable dataset
	- Supermarkets: still looking for a suitable dataset
	- Zip code/ address: TIGER/Line Shapefile, 2016, Series Information for the Address Ranges County-based Relationship File
	- Weather: Global Forecast System

* Map View
	- The initialized map is located at where the user is or West Lafayette. The user can change the map with zip code or address.
	- The user can set a custom distance range.
	- Local farmers and supermarkets nearby are showed with different types of tags that users can distinguish the differences easily.
	- Special events or discounts are showed with a more eye-catching tag.

* Data Visualization
	- The user adjusts his/her preferences with a radar chart.
	- By selecting multiple farmers and supermarkets, the application will show a comparison table.

* Interaction Form
	- Information input: location, distance range, expected shopping time
	- Operation option: preferences (farmer/supermarket, freshness, price, rating, distance..)
	- Interaction with the map: address/zip code input, zoom in/out, select farmer/supermarket tags
	- Information output:
		Multiple selection: a comparison table
		Single selection: detailed information for a certain tag shows in a popup

* Content
	- README.txt: this file.
	- index.html: application page.
	- style.css: css style file.
	- js: a directory of javascript files.
	- img: a directory of images.

### Build up Information
The application is built up with HTML/CSS/JavaScript. For front-end platform, it uses Bootstrap. For data visualization, it uses D3.js.  

### Test
* Browsers: Chrome, Safari, Firefox, IE
* Devices: computer, tablet, mobile phone
