# Bikesharing


## Overview

The purpose of this analysis was to put together a compelling dashboard and story in Tableau to persuade investors to fund a bikesharing business in Des Moines. Analysis was performed on a dataset from Citi Bike Trip Histories where a variety of fields were collected in NYC during the month of August in 2019. The fields collected included: trip duration, start/stop time and date, start/end station name, station ID, station lat/lng, bike ID, user type, gender, and year of birth. Analysis was done on the month of August because there is likely more traffic during the summer months. While the data comes from bike trips in NYC, the goal of the analysis was to identify which data will apply to Des Moines so that a business model can be proposed to investors.

[link to dashboard](https://public.tableau.com/app/profile/aleah.kitahara/viz/Citibike_Mod15_Challenge/Story1)


## Results

![Story_1](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_1.png)

The first story point describes the breakdown of customer type and total number of rides. There were a total of 2,344,224 trips recorded. The majority of rides were from those subscribed to Citi Bike which will help us predict the customer breakdown in Des Moines. The gender breakdown revealed that the majority of users identified as male, followed by female, then unknown. 


![Story_2](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_2.png)

Next the count of trips by weekday and hour of day were visualized in a heatmap. This was done to gain insight on the most popular usage times throughout the week. The heatmap indicates a higher count of trips during the working hours of the day and weekends. From Monday through Friday there is an increase in trips from 6AM to 9AM and 4PM to 8PM. This could be attributed to users going to and from work during these hours. Saturday and Sunday show relatively consistent use throughout normal daytime hours, which could be due to customers being off work or tourism on weekends.


![Story_3](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_3.png)

Next a visualization was created to dig deeper into the count of trips by weekday and hour of the day. This created sections based on gender to identify if there was a difference in usage. Overall, there is a similar pattern of usage between female, male, and unknown  users. The only difference is the intensity of the sections due to the majority of customers being male, then female, and unknown with the fewest count.


![Story_4](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_4.png)

A visualization was created to display the breakdown of user type trips by weekday and gender. The purpose was to see if there is a  difference trip count based on user type throughout the week. The users were then divided into gender categories. The highest count of trips occurs in male subscribers followed by female subscribers. The unknown gender has higher counts of trips in the customer field and substantially lower counts in the subscriber field. 


![Story_5](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_5.png)

Next, tripduration was measured per number of rides. This visualization shows that the majority of trips lasted approximately five minutes (peak). The overall trend is that most trips are for a short duration, which means the main use of bikes are for short commutes. This could be attributed to being located in a city with destinations in close proximity to starting points. As tripduration increases past ten minutes the number of trips decreases.


![Story_6](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_6.png)

A similar visualization was created to look at the role of gender in relation to tripduration and number of rides. Across the male, female, and unknown gender there is a similar trend. The majority of rides are short-term. Male and female riders show an almost identical curve with the majority of rides being approximately five minutes. The unknown gender shows a majority of rides being eleven minutes which plateaus until the twenty-five minute mark. 


![Story_7](https://github.com/Aleahkita/Bikesharing/blob/main/Pictures/Story_7.png)

The final visualization shows the starting locations with markers' size and color indicating count of trips. The majority of markers are central to the city and disperse outward as you go away from the center. This can provide useful information on where bikes are in demand. 


## Summary

The customer base is mainly made up of male subscribers, with the majority of user type being subscriber and gender being male. In the gender breakdown, male represents the majority followed by female and then unknown. The most popular times throughout the week seem to be during commuting hours on weekdays where we can assume there is a demand for bikes as people go to and from work. There is a steady count of trips throughout the daytime hours of the weekend which can be attributed to tourism and customers being off of work. There are similar usage trends between all genders. There are also similar usage trends when the same statistic is broken up by user type. The most frequent tripduration is around five minutes which indicates the bikes are being used for short commutes. Also, taking into account that the location where data was collected is a city it can be said that starting and stopping destinations would be in close proximity. There are similar trends for tripduration between genders, with only a slight difference in the unknown gender. The unknown gender has a majority of trips lasting eleven minutes and plateauing until the twenty-five minute mark. A concentration of trips by starting location can be seen around Manhattan. Usage can be attributed to tourism in the densely packed city area or concentration of population.

An additional visualization I would create would be a bar chart of the top twenty starting stations (each bar representing a count of station names) to show the general areas of starting. This could be useful in identifying areas to drop off fully charged bikes to meet demand in these areas. Another visualization I could create would be a of count of rides by age. There would be set age ranges with the count of rides for each range. This could be valuable in identifying a target demographic when it comes to advertising. 
