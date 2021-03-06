# NFLX-Bootcamp-Final-Project-Group-1

TITLE:  Road Safety and FSD Beta Testing

Link to our presentation: https://docs.google.com/presentation/d/1-2pEwJYZjQ5pkEPXfl2XwbFrKclrtm97GATm0gh5Vns/edit?usp=sharing

PURPOSE:
    The purpose of this project is to prepare Tesla on its roll out of its FSD beta testing in the UK, 
based on accident data collected in the UK during 2020.

MAIN QUESTION:   What factors lead to accidents and how could they be avoided?

GUIDING QUESTIONS:

   1. When do most accidents happen?  
   2. How does speed limit play a role in the number of casualties of an accident?
   3. How are road conditions associated with the number of casualties? 
   4. Where do the most severe accidents occur?

------------------------------------------------------------------------------------------

ANALYSIS #1: Time

Hypothesis: If time of day impacts death during accidents, then the rate of casualties will vary throughout day

Null: Rate of casualties in accidents does not differ between each block of time

Alternative: Rate of casualties in accidents is different based on the time of day


We separated each hour of the day into time blocks: Early Day, Morning Rush, Day, Evening Rush, Night and Late Night. Most casualties happened during Evening Rush Hour and Day, with the lowest being Night and Late Night. However, when we looked at average casualties, Night and Late Night had the highest average. Where we do not see a significant difference is in the late night and night time accidents, early day and evening rush hours, and daytime and evening rush hours, possibly due to people getting to work during different hours.


CONCLUSION: We reject the null hypothesis. There is a difference in the rate of casualties based on the time of day.

------------------------------------------------------------------------------------------

ANALYSIS #2: Speed

Hypothesis: If speed limits impact the amount of casualties in an accident, then the average rate of casualties will increase in higher speed limit areas

Null: Speed limits do not have an impact on the average number of casualties

Alternative: Speed limits do have an impact on the average number of casualties and higher speed limits have a higher casualty rate


We saw that there were a lot of casualties for the 30 speed limit. This can be because there are more distrations and more things to look out for, like pedestrians and bikers, on regular streest versus on a highway. Also, people are more often going to be driving on regular streets than on a highway. Our test showed that as the speed limit increases, the number of casualties increase as well. 


CONCLUSION: We reject the null hypothesis. Higher speed limits affects the rate of casualties.


------------------------------------------------------------------------------------------


ANALYSIS #3: Road Condition


Hypothesis: If road conditions impacts the number of casualties in an accident, then the number of casualties will increase when road conditions are not dry 

Null: Road conditions do not impact the number of casualties of accidents

Alternative: Road conditions do impact the number of casualties of accidents


For all road conditions, most accidents only involved only 1 casualty. Dry had the highest percentage of accidents involving 1 casualty, 82%, and Snow had the  lowest, 71%. As we get to accidents that involve 2 or more casualties, we found that Dry road conditions have the lowest percentage across all road conditions. Driving in non Dry conditions has a likelier chance of higher number of casualties. This is supported by our ANOVA test, which showed that Dry condition was statistically different. Also, when we calculated the average number of casualties for all road conditions, Dry was the lowest, with 1.25 and Flood was the highest, with 1.37.


CONCLUSION: We reject the null hypothesis. Road conditions do impact the number of casualties, specifically road conditions that are not Dry.


------------------------------------------------------------------------------------------


ANALYSIS #4: Location

Hypothesis: If location is a factor in the severity of accidents, then severity rates will differ in urban and rural locations

Null: Location does not impact severity of accidents and does not change whether it is in an urban or rural location

Alternative: Location does impact the severity of accidents, and they are more severe in rural than urban locations


The data showed that there were roughly 2 times the amount of urban accidents as there were rural ones. This is supported by the map because it showed that most accidents happened around big cities, like London and Birmingham. Most of these accidents were slight or serious, in terms of severity.


CONCLUSION: We reject the null hypothesis. Location does affect the severity of accidents, specifically in rural areas. 

------------------------------------------------------------------------------------------


SUMMARY:

Overall we found: 

   1. The Rate of casualties in accidents does differ during the day
   2. Faster speeds in comparison to slower ones have higher rate of casualties
   3. Road conditions do impact the number of casualties of accidents
   4. Location does impact the severity of accidents, and they are more severe in rural than urban locations


RECOMMENDATION:

   1. When implementing the Full self driving beta testing, Tesla can check for driver attention by asking them to pull on the wheel more often than usual whenever they are driving in streets with lower speed and advise against high speed testing
   2. They can also warn drivers to test when road conditions are dry.
   3. They can rollout beta besting to primarily urban areas since there are less severe accidents that occur in urban areas. 
