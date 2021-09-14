# Minimum Viable Product

The goal is to find the best subway stations to place street teams to hand out flyers to the gala. 
We are assuming the stations with the highest traffic are the best ones. 
In addition, let's try to find stations that are more likely to be used by *commuters* as opposed to tourists; tourists are unlikely to be in 
town the night of the gala. 
Thus, I’m looking at stations that have high traffic during morning and evening rush hours. Due to the way the MTA set up their system, I have currently defined morning rush hour as 8 to 9:30 am, and evening rush hour as 5 to 8 pm.

Below is the graph of the highest average **entries** in the morning. 

<img src="https://raw.githubusercontent.com/cda913/EDA_Metis/main/allAM.png" width="400" height="350" />

Below is the graph of the highest average **exits** in the evening. 

<img src="https://raw.githubusercontent.com/cda913/EDA_Metis/main/allPM.png" width="400" height="350" />

### A couple of things to note:
- Journal Square is a transportation hub and therefore the large difference may be accurate. 
- The top 20 stations are not the same. This is likely due to the time range difference between the two graphs.
- The y-range on the graphs is not the same. This may be due to the time range differences, but I will be investigating this

## Still to do
As stated in things to note, I need to look at why there are so many more exits than entrances. In addition, I will be looking at the exits in the morning and the entries in the evening, which may get different results. Finally, I plan to extend the morning rush hour to include the 12 pm numbers from the MTA data.

