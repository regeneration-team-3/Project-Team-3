<html>

<p align="left"><img width="1000" height="auto" src="Images/header.PNG"></p>          

<body>

<p>

 

# Predicting the City-Cycle Fuel Consumption in Miles per Gallon of a Car: Project Overview 
This Group Project was made during ReGeneration Academy on Data Science(powered by Papastratos) during September/October 2021.
 
* Created a tool that estimates Miles per Gallon(mpg) to present it to a car rentinig company in order to use it when reniewing her car fleet.

* Dataset used had data for 400 cars provided by Airbnb.

* Made 2 Dashboards using Microsoft Power BI, 

* Optimized Linear, SVR, and Linear SVR  Regressors using Voting Regressor to reach the best model. 
 
<h3>Final Submissions<h3>

* Overview of the Data with Power BI (D01)

* Exploratory Data Analysis (D02)

* Preprocessing (D03)

* Dashboard with Power BI (D04)

* Machine Learning Model (D05)

* Conclusions (Presentation of our Data Product)




## Code and Resources Used 

**Python Version:** 3.7  
 
**Platforms:** Jupiter Notebooks
 
**Visualization Tools:** Microsoft Power BI

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, 

## Dataset Overview (PowerBI)
 
## Data Cleaning

We needed to clean it up so that it was usable for our model. We made the following changes and created the following variables:



*  

*  

*  

*  



## EDA

We looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights. 


## Dataset Overview(after Cleaning & EDA analysis) 

## Model Building 


First, We transformed the categorical variables into dummy variables. We also split the data into train and tests sets with a test size of 30%.   


We tried multiple different models and evaluated them using Mean Absolute Error, .    


## Model performance

The Voting Regression model far outperformed the other approaches on the test and validation sets. 


<br>
<br>
<p align="center"><kbd><img width="1000" height="100" src="Images/header.PNG"></kbd></p><br>                     
<br>
</body>
</html>
