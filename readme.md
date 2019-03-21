# Ford GoBike System Data Exploration
## by Chunan Lin


## Dataset

The data consist of nearly 45000 bike riding records in 2007 accroding to the Ford GoBike System, a bike sharing system. There are multiple features including the geographic location of station, duration of trip, member birth year and member gender. The data can be found [here] (https://www.fordgobike.com/system-data).

I used member birth year to calculate and create a new variable that contains each user age. Then I used geographic location to calculated the distance of the trip. Then I separate member ages in to several age group (under 18, 18-35, 36-55, over 55). Then I convert gender, user type and age group into categroy type.



## Summary of Findings

In the exploration, I found multiple linear relationship between distance and duration. The user type can be the third variable that can influence the distance vs duration relationship. 
Besides that, even though the customers have a small proportion of the total amount of users, the customers group has more average distance and average duration than subscriber group, which means the customers usually take more time to ride bike and travel a longer distance in one ride.

For the presentation, I will focus on the linear relationship between distance and duration, and how user type will change the linear relationship.


## Key Insights for Presentation

First, I start by introducing the features of the dataset by categorical type and numeric type. Then I introduce the feature I added for the exploration, which is distance. 
Moving on to the visualization, I introduce the distribution of the duration and give explanation for the unusual range of the duration. 
Then I use the scatter plot between duration and distance since it shows a obvious relationship. Then I point out an interesting fact that how user type will effect the relationship between duration and distance by showing the FacetGrid of the two scatter plot of customer and subscriber user type.