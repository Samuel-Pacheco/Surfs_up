# Surfs_up

# Overview of Surfs Up Analysis
Useing VS code, Weather analysis using SQLite and SQLAlchemy. Climate App building using Flask. Other tools include Python and Jupyter Notebooks.
The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database to provide information that will convince an investor that opening up a Surf n' Shake shop in Oahu, Hawaii is a good business idea.
In order to explore the data in the SQLite database, we used SQLAlchemy to connect and generate queries to pull the necessary information needed for our analysis.

# Results
 we first looked at the the precipitation for a one year timeframe, We reviewed the activity from August 23, 2016 - August 23, 2017.
 The average was 18% based on 2,021 observations.
 
 ![image](https://user-images.githubusercontent.com/53358476/194982856-84801152-d82b-472e-930d-cac4021c179b.png)
 
 We then expanded our results to look at all of the observations that were recorded in the month of June and December regardless of year, the results showed:

  - The average temperature is in the 70's.

  - Both June and December showed similar min/max and average temperatures.

  - The assumption is that the temperature does not have dramatic fluctuations throughout the year.

![June Pre-Temp](https://user-images.githubusercontent.com/53358476/194983052-9eb2c222-2846-495d-9ee6-a66468dfed5f.PNG)

![Dec Pre-Temp](https://user-images.githubusercontent.com/53358476/194983081-b7cac6f8-4f99-4797-aa39-70eebb97ca03.PNG)

# Summary

the temperature in Oahu is relatively the same throughout the year and the chances of continuous rainfall is low. When we rewrite the queries to add precipitation to the results for June and December, the average precipitation in those months

- June at 14%
- December at 22%

![image](https://user-images.githubusercontent.com/53358476/194983762-4daf8f6b-ccc3-4a0d-9fed-a3ca069774d5.png)

![image](https://user-images.githubusercontent.com/53358476/194983817-f5c82e8c-a901-4b5b-a917-029bba7a8cc5.png)

