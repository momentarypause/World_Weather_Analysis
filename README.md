# World_Weather_Analysis

## Purpose
The purpose of this project is to connect to Google APIs to create interactive maps to assist a customer in planning out a vacation according to specific weather preferences.

## Included in this repository

### Weather_Database Folder
[Code](Weather_Database/Weather_Database.ipynb)  for randomly generating 2,000 random latitude and longitude coordinates, retrieving the nearest city, and gathering weather data about each. This dataframe is saved into a [CSV file] .

### Vacation_Search Folder
[Code]  that accesses the CSV file created in the Weather_Database folder to allow filtering of cities by maximum and minimum desired temperatures as well as retrieving a nearby hotel for each, saved into another [CSV file] .  This data is used to create a [map] with markers at each filtered city with information for Hotel Name, City, Country, and Current Weather.

### Vacation_Itinerary Folder
Four cities were chosen within the same country to plot a possible vacation itinerary for the customer.  This [code] plots these cities on a [map] showing the driving route between them. Also included is the same [map] with markers that show Hotel Name, City, Country, and Current Weather.
