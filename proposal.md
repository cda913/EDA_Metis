# Proposal for MTA Subway Data

Karrine and Dahlia at WTWY would like to use MTA subway data to "optimize the placement of our street teams". 

### Question.
We want to find subways that are busy; more people means more chances to get someone to sign up. We need to find multiple locations; WTWY want to cover the entire city. We need to take time into consideration; people exiting at 3 may be more likely to be tourists than residents. 

### Data
I will use the MTA data set to find which stations have the highest flow at rush hours and lunch times during the week over the last 6 months. I'll be using 6 months due to the season - many offices have summer hours. 

### Tools
I will use SQL to pull the data from the MTA database; Pandas to clean the data; and Matplotlib to graph stations. One graph will show the stations flow going **out** sorted by volume; one graph will show the flow going **in** sorted by volume. Graphs will not have all stations; the number of stations on the graphs will depend on what I find during analysis. 

### MVP
MVP will be one week's worth of data, as that is the size of each file from MTA. 
