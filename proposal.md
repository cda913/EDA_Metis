# Proposal for MTA Subway Data

Karrine and Dahlia at WomenTechWomenYes (WTWY) would like to use MTA subway data to "optimize the placement of our street teams". 

### Question.
We need to find subways that are busy: more people means more chances to get someone to sign up. We want to find multiple locations: WTWY wants to cover the entire city. We want to take time into consideration: people exiting at 3 may be more likely to be tourists than residents. We want to look at entries vs. exits: people may be in more of a hurry and less likely to stop at one or the other.

### Data
I will use the MTA data set to find which stations have the highest flow at rush hour over the last 6 months. I'll be using 6 months due to the season - many offices have summer hours. 

### Tools
I will use SQL to pull the data from the MTA database; Pandas to clean the data; and Matplotlib to create graphs. The plan is to have two graphs. One graph will show the stations flow going **out** sorted by volume; one graph will show the flow going **in** sorted by volume. Graphs will not have all stations; the number of stations on the graphs will depend on what I find during analysis. 

### MVP
MVP will be the most visited locations overall, rather than broken out by time, over one week (the minimum file size from the MTA). 
