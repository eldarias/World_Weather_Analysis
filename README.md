# World Weather Analysis

## About this Challenge
This challenge consisted of three deliverables which required putting into practice what had been learned in the module.  The main libraries used were: pandas, motplotlib, numpy, citipy and gmaps.

The **first deliverable** was to retrieve Weather Data by generating 2,000 random latitudes and longitudes, then performed API calls to OpenWeatherMAP to retrieve information from valid coordinates.  The output was parsed and the required fields were added to a new DataFrame.  The columns were properly sorted and the DataFrame was saved/exported as a CSV File.

The **second deliverable** was to create a Customer Travel Destinations map from the data collected from the first deliverable.  The CSV file was imported into a DataFrame then sorted based on a minimum and maximum temperature.  Empty rows were removed from the DataFrame and the Hotel Names column added.  Nearby hotels were retrieved and added to the Hotel Names by performing API queries to Google Directions APIs using the latitude and longitude among other parameters.  The Google marker layer map was used to visualize all hotels/locations and display only the required fields.

The **third deliverable** consisted of creating a Travel Itinerary Map.  The dataset from the second deliverable was used.  The Google Directions API was used to create a travel itinerary that showed routes between four cities.  The data was visualized via a marker layer map with pop-up markers for each city in the itinerary.
