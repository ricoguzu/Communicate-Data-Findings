# (Dataset Exploration Title)
## by (your name here)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The dataset has 174952 entries with 22 columns after data wrangling.


## Summary of Findings

> In the exploration I found that most trips were on Thursdays and Tuesdays. Weekends have the least trip records, although longer duration compares to other weekdays. One interesting thing I also found is the higher trip records for the 8th and 9th hours in the morning and the 17th and 18th hours in the evening. 

>I found that customers spend much more duration on their trips than subscribers and other gender tend to ride for more duration than males. and females

>Majority of the users did not use the bike share for all trips and having the other gender have long trip duration on both yes and non bike sharing for all trip.


## Key Insights for Presentation

>For the presentation, I will focus on the frequencies of the rides per hour, day, and user type and leave out leave out most of the intermediate derivations.I start by checking out trip frequencies by hours and days of the week and the user type using seaborn countplot.

>Afterwards, I introduce each of the categorical variables one by one. To start, I use the boxplot plots of duration across days and user type. The other two categorical variables, days and user type, are covered afterwards, using point plots. I've made sure to use different color palettes for each quality variable to make sure is clear that they're different between plots.