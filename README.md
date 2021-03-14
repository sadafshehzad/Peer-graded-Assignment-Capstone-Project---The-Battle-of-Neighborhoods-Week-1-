# Peer-graded-Assignment-Capstone-Project---The-Battle-of-Neighborhoods-Week-1-
Applied Data Science Capstone
Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods

Project Title:
“Guiding my Non-Pakistani colleagues to locate different food places, shopping malls and activities in the city Karachi, Pakistan.”
By: Sadaf Shehzad

1. Introduction/Business Problem:
The purpose of this Capstone Project is to help people in exploring best venues for malls and other social places around the Hotel Marriott, Karachi, Pakistan.
 It will also help people making smart and efficient choices on selecting great food places in different places in Karachi.
Karachi is the largest city in Pakistan and the twelfth largest city in the world. It is the capital of the Pakistani province of Sindh. Karachi is Pakistan's premier industrial and financial center.
Karachi is known as the "City of Lights".
Approximately 90% of the multinational corporations operating in Pakistan are headquartered in Karachi. 
Last year a group of my colleagues had to visit Karachi on a business trip. They were staying in Marriott Hotel, Karachi. They inquired me about some of the best places to dine out, shopping and social gathering places.
So, I thought to make a project for my colleagues. Specifically, this report can provide a reference for any one, visiting Karachi for the first time, and those who are interested in exploring the different cuisines and shopping, offered there.

Foursquare API Data:
We will need data about different venues in different addresses of the places around Hotel Marriott. In order to gain that information, we will use “Foursquare” locational information. Foursquare is a location data provider with information about all manner of venues and events within an area of interest. Such information includes venue names, locations, menus and even photos. As such, the foursquare location platform will be used as the sole data source since all the stated required information can be obtained through the API.
After finding latitude and longitude of Hotel Marriott, we then connect to the Foursquare API to gather information about venues around that place.
The data retrieved from Foursquare contained information of venues (of food places , snack places , shopping malls and social places) within a specified distance of the longitude and latitude of the Hotel Marriott. 
Use a clustering model to find similar areas based on the categories.
2. Data
In this project, we will fetch or extract data from the following data sources:
1.	To find the latitude longitude of Pakistan and all the cities of Pakistan using:
         https://simplemaps.com/data/pk-cities
2.	Using Folium library to generate Pakistan map and locate its different cities to give my Colleagues a general idea if Pakistan’s lay out.
3.	Using Karachi’s latitude and Longitude with Foursquare API to find its best Venues.
 


Folium
Folium builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the leaflet.js library. Manipulate your data in Python, then visualize it in on a Leaflet map via folium.
3. Methodology
For this report I used a few different maps that could help anyone visiting Pakistan for the first time to get the knowledge of its layout on the world map, its Provinces and major cities on the map and then to finally explore in detail the city they are visiting , Karachi , in in this case.
The maps and data frames will help them decide the best Food places, shopping malls , social activity places. 
In order to do that I've used the Foursquare API to gather information around Hotel Marriott and the use K means Clustering technique to group/ cluster different addresses in Karachi based on the categories.
 
Then using Folium maps to visually display the different groups of categories around Hotel Marriott, which ultimately help them navigate easily through the map.
4.Conclusion:
Comparing the colored clusters on the map we can notice most of the restaurants, represented by orange clusters, grouped in the main city are towards downtown, although some of are up to the north from the Hotel. Most of the shopping places, representing by purple clusters, are in the north direction from the Hotel. 

Cluster 0: ORANGE: FAST FOOD RESTUARANTS.
Cluster 1: PURPLE: MARKET PLACES, SHOPPENG MALLS.
