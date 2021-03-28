Data:

To solve the problem, we will need the following data:
• List of SubUrbs in Sydney and Melbourne.
• Latitude and longitude coordinates of those SubUrbs. This is required in order to plot the map and also to get the venue data.
• Venue data, particularly the top 10 venues. We will use this data to perform clustering on the neighbourhoods.

Sources of Data and methods to extract the Data:

Wer are using BeautifulSoup package to extract the  is a list of SubUrbs in Sydney and Melbourne. 
We are using web scraping techniques to extract data from Australia Post website, extracting the list of postal codes in the areas and removing the duplicates. 
Foursquare API will provide many categories of the venue data, and we are particularly interested in the top 10 venues in each Suburb to help us solve the business problem. 
This is a project that will make use of many data science skills, from web scraping (Wikipedia), working with API (Foursquare), data cleaning, data wrangling, to machine learning (K-means clustering) and map visualization (Folium).

Methodology:

The Foursquare API allows application developers to interact with the Foursquare platform. The API itself is a RESTful set of addresses to which you can send requests, so there’s really nothing to download onto your server.
