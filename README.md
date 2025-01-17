# DataSciencePoject

# Introduction
  The objective of our project was to practice visualizing data in Python. Specifiaclly we wanted to look at data conerning videogames sales to see if we could create charts to answer the three questions we had. Those question were:
  
   1. How many games in each genre?
        
   2. Does the User_Score correlate with the Critic_Score?
    
   3. What is the breakdown of games sold on each Platform every year?


# Selection of Data
  All data manipualtion and visualization was done in a Juypter notebook (https://github.com/edyer01/DataSciencePoject/blob/main/DS_Final_Videogame_Data.ipynb)

  The data was taken from a set found on Kaggle (https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)
  
  The data has 16 characteristics: Name, Platform, Year_of_Release, Genre, Publisher, NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales, Critic_Score, Critic_Count, User_Score, User_Count, Developer, and Rating
  
  After looking through the data, we realzied that many of our data points had incomplete infromation. We decided the best way to deal with this was to simply remove any data entry that was missing information. This took our data sample down from a size of roughly 16000 to 6000, which we felt was still enough of a smaple size to anser our questoins.

# Methods
  Tools: 
  
   Pandas for data cleaning and analysis
   
   matplotlib.pyplot and seaborn for data visualization
          

# Results
  Question 1:
  ![alt text](https://github.com/edyer01/DataSciencePoject/blob/main/Q1.jpg)
  
  Question 2:
  ![alt text](https://github.com/edyer01/DataSciencePoject/blob/main/Q2.jpg)
  
  Question 3:
  ![alt text](https://github.com/edyer01/DataSciencePoject/blob/main/Q3.jpg)
  
  To answer this question, we decided to create a stacked area graph. Each color represents one platform, and the area of that color shows how many total games were sold globably on that specific platform for that year.

# Discussion
Question 1:

Question 2:

Question 3:
 
 The most interesting result from this graph is how quickly games sales for a platfrom drop off when a newer version of the platfrom is released. The reason behind this dropoff could be from two potential reasons. First, it could be becuase when a new version of a platform is released, video game publishers all stop publishing games on old platforms as they look to publish games on the new platform instead. Similarly, the release of a new platfrom could prompt all users of the old platfrom to stop buying games on the old platform as they have purchased the new platfrom and are purchasing games on that platfrom instead.

# References
  https://www.geeksforgeeks.org/pandas-groupby-multiple-values-and-plotting-results/
  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.area.html
