# Citi-Bike Jersey City 2020 Analysis

This is a combined python ETL along with Tableau Analysis Project. This analysis was broken up into two phases:

1. ETL Phase: The data, as provided, is broken up per month. I wanted a single csv file to present to Tableau so I used some loops in python to read in the data and concatenate it. I also used a function to add in a new field to the data, Distance (miles). The distance is calculated using the geopy.distance module. Calling distance.distance with two sets of latlng parameters returns the distance in miles between these two points of interest.
2. The second phase is the Tableau Data Visualization/Analysis phase. In this phase, I created a total of ten graphs, two dashboards, and one story that combined all of these visualizations and provided analysis for them in a story form.
