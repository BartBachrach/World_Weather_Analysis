# Vacation Search, Planning, and Itinerary
## Overview
During this process we created maps and code to filter global locations based on parameters set by a user input. The input regarded temperature, a minimum and maximum temperature for a vacation.  We mapped the cities with those weather parameters, then searched for nearby hotels in those cities for our users to stay in. 
They wanted to have a road trip, so we mapped them a route between four cities with those weather parameters and created labels on the maps with the cities’ name, country, max temp, and current weather description. 

## Methods
We queried Google’s Nearby Places and Directions API’sn to collect this information. The first step was generating an API key, which is personal and should NEVER be posted publicly. We wrote code to prompt the user to input their desired temperatures, and those inputs were used as the parameters for the global location search. We wanted a nice sunny, warm place to go for vacation, so we chose locations whose average temperatures were between 75 and 90 degrees Fahrenheit. The locations were largely located between the equator and the tropics of cancer and capricorn. 

From that point we selected four cities we’d like to visit, and queried Google’s Directions API to generate a travel route between the four cities to make a loop. 

Finally, we added a marker layer to the map to show the locations’ city name, country name, max temperature for the day, and current weather description. 

## Final Result
We elected to visit four cities in the American southwest which fit our criteria. I cannot say the four selected cities would be terribly fun to travel to, but it is proof the code and concept were sound. 
