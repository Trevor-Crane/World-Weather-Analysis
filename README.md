# World-Weather-Analysis

## Project Overview
A new app, the PlanMyTrip app, has asked me to program a few changes. First off, we will add the current weather condition to the travel destinations. Next, we will create a questionaire to ask potential beta testers to filter their data for their weather preference, which will then be used to find potential travel destinations and nearby hotels. Finally, we will add a travel destination with four nearby cities to where the beta tester chose. This will all be done by using Python, while using Jupyter Notebook.

## Retrieving Weather Data
We will first be randomly generating 2000 global coordinates. Then, we will map out the closest city to each one, barring their is one with the generated set, and the city chosen hasn't already been added to the list. We will then call upon an API to find the current weather conditions. This will give us weather, such as the maximum temperature, wind spped, and  current weather conditions.

## Creating Travel Destinations Map
Using the data we have just generated, we will now ask a beta tester what their preference to temperature is. Using their answer, we will limit our possible destinations to the perameters they have chosen. We will then create a map with potential travel destinations, and hotels that are nearby those locations.

## Creating a Travel Itinerary Map
Finally, with the city they have chosen, we have created a route with three nearby city locations for the beta tester to choose to go to. We showed the same information as before, ie nearby hotel and current weather condition. 
