# Ride Sharing Investment Analysis
Module14 Challenge
## Overview of Analysis
We are working to bring a bike share program to Des Moines. Our investors want to see bike share data, so we are using New York CitiShare bike data to create charts and graphs for them in Tableau. These charts and graphs will be used for a business proposal to bring the bikes to Des Moines.

## Bike Usage by Gender
![data1.png](https://raw.githubusercontent.com/LaurenDebes/BikeSharing/main/data1.png) 
The first pie graph shows bike users by gender; it shows most bike users (65%) are male. Then we looked at how trip duration by gender. The chart for men is heavily skewed right, with the most bikes being rode for about 5 minutes and almost completely tapering off (less than 1,000 users) after an hour. Women follow a similar pattern, but with less users. For unknown gender users, they have less of a spike in use and tend to follow a more steady plateau in use time, but still hardly any use the bikes for more than an hour.

![data1.png](https://raw.githubusercontent.com/LaurenDebes/BikeSharing/main/data1.png) 

## Overall Trip Duration
![data2.png](https://raw.githubusercontent.com/LaurenDebes/BikeSharing/main/data2.png) 
This graph shows the duration of time on the bikes by number of users. Most users ride the bikes for about five minutes, with a gradual decrease until an hour where almost no users (less than 1,000) use the bikes. 

![ttests.png](https://raw.githubusercontent.com/LaurenDebes/MechaCar_Statistical_Analysis/main/ttests.png)

## Study Design: MechaCar vs Competition
We are looking to design a study to compare the manufacturing costs of MechaCar cars to the competition (other manufacturers in a similar price range). 
- We will be looking at the following metrics per manufacturer and within the building plants:
  - Total Cost
  - Total Labor Cost
  - Total Manufacturing Time
  - Cost of Parts
- Null Hypothesis: The costs are the same, any differences can be explained by random chance
- Alternative Hypothesis: The costs are different, the differences are not explained by random chance
- Statistical test to run:
  - Because we will be using a large data set, using a numerical success metric, and comparing two data from two different data sets, we can use a two-sample t-test. This will answer if there is a statistical difference between the distribution means from the two samples. 
- Data Needed to Run Test:
  - Data on individual manufacturing plants for MechaCar vs competition manufacturers
  - We will need data on total cost including labor (standardized to the same currency), labor cost by itself, manufacturing time from start to finish, and the total cost for parts. We will need to make sure the data is normal and follows the correct assumptions.
 
