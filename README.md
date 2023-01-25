# Reproducible-Research
The Monetary and Social Effects of Natural Disasters
Natural disasters including earthquakes , floods, typhoons, and hurricanes are causing serious damage and so tend to be negative for the economy. For companies, natural disasters destroying and deteriorating their production capacities are tangible assets such as buildings and equipment as well as human capital. Often such negative effects may be detrimental to businesses and force them to shut down.

Here in this paper, I will try to point out some disasters that do more damage than others, and will try to find the average property damage by event. Whatsoever, I will use the data collected by the National Climatic Data Center in the United States, will make the analysis for common readers to understand the effects of those certain natural disaster, and will show how many people do get affected by those unexpected events. However, by the end of the paper, the analysis will answer the questions such as which types of events are most harmful with respect to population health, and which types of events have the greatest economic consequences across the United States.

Data Description
The National Climatic Data Center (NCDC) receives Storm Data from the National Weather Service. The National Weather service receives their information from a variety of sources, which include but are not limited to: county, state and federal emergency management officials, local law enforcement officials, skywarn spotters, NWS damage surveys, newspaper clipping services, the insurance industry and the general public.

The NWS has 60 days to submit their data files to the NWS Headquarters in Silver Spring, MD. The NWS Headquarters (NWSHQ) then collects all of the data files from the 124 NWS Forecast Offices (NWSFO). The NWSHQ then uses several algorithms to prepare the Storm Data product into the integrated database. The NCDC receives a copy of this database approximately 75-90 days after the end of the month. A publication and archive are produced and the Storm Events Database is then updated within 90-120 days after the end of the month.

The National Weather Service makes a best guess using all available data at the time of the publication. The damage amounts are received from a variety of sources, including those listed above in the Data Sources section. Property and Crop damage should be considered as a broad estimate.

Data Processing
This is an example of how the data is stored.









Across the United States, 985 types of events do happen, as it can be seen from the table below.








Calculate the events that caused injuries or fatalities, and categorize them by the event name.








We get the events that harmed at least 1 person to narrow down the situation. Then, proceed to sort the data in descending order.










Plotting the graph of the events that harmed more than 1000 people.











Finding the events that caused property damages, categorized by event name.










Also, sorting the table just given above in a descending order.










Narrowing down the 406 objects from the table above by limiting the property damage by minimum of $10,000. After that, Plotting the the subset I did get by narrowing down, and putting labels to see the exact numbers for the events caused more than 450,000 dollars in damage.











Merging the two dataset I did manage to get above, and continuing to create another data frame with a frequence for every event. With the frequence, I did divide the property damage by frequency to find an average to decide which one is more harmful than others in economic context.



Results
Across the United States, which types of events are most harmful with respect to population health?









As it can be clearly seen from the plots generated and the data set from above, natural disasters like tornado, lightning, flood and wind do seem to cause the most harm to people. Given the ratio of whenever the natural disaster was present averagely the number of people injured. The most damaging of the four do seem to be the tornado, approximately 1.6 people get injured whenever the disaster showed itself. Following that, Lightning do also injure people, which was unexpected for me of it being the second most, even higher than the floods.

Across the United States, which types of events have the greatest economic consequences?









Economically, the most damaging events are the almost the same as the ones that harmed people the most. As it can be seen from the data table above, Tornado, also here is the most damaging natural event. Every tornado nearly caused 63 in monetary damage. The second and the third closely following the tornado are lightning and flood. Lightning, contrarily caused less damage on property than tornado. Floods on the other hand, do seem to be occuring more frequently than the lightning, and damages almost equally as the lightning, which is definetely a problem. Flash floods' frequency is incredible high, and caused total damage of equally to both lightning and flood together. Which is definetely poses a great problem, given the monetary damage.
