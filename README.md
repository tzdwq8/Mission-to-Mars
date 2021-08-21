# Mission to Mars

## Project Overview
The purpose of this project is to build a web application to automate the construction of a webpage concerning the Mission to Mars.  This script is intended to gather the latest news, which can be updated regularly.

Data Sources: [Mars News](https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest), [Mars Featured Images](https://spaceimages-mars.com/), [Mars Facts](https://galaxyfacts-mars.com/), [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) 

Steps include:
- Chrome Developer Tools to identify HTML components
- BeautifulSoup and Splinter to automate web scrape
- Mongo to store the data
- Flask to display the data
