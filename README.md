<html>

<p align="left"><img width="1000" height="auto" src="Images/header.PNG"></p>          

<body>

<p>


T

The project intertwines Power BI and Machine learning to predict city-cycle fuel consumption in miles per gallon of a car.
 
<h3>Final Submissions<h3>
 
<h4> Overview of the Data with Power BI (D01)
<h4> Exploratory Data Analysis (D02)
<h4> Preprocessing (D03)
<h4> Dashboard with Power BI (D04)
<h4> Machine Learning Model (D05)
<h4> Conclusions (Presentation of our Data Product)
 
 
 
<h3> Interim Submissions<h3>

 
 
<h3> Scrapbook<h3>
<h4>Our tries, approaches and versions before submissions.


# Predicting the City-Cycle Fuel Consumption in Miles per Gallon of a Car: Project Overview 
This Group Project was made during ReGeneration Academy on Data Science(powered by Papastratos) during September/October 2021.
 
* Created a tool that estimates Miles per Gallon(mpg) to present it to a car rentinig company in order to use it when reniewing her car fleet.

* Dataset used had 400 cars provided by Airbnb.

* Made 2 Dashboards using Microsoft Power BI, 

* Optimized Linear, SVR, and Linear SVR  Regressors using Voting Regressor to reach the best model. 


## Code and Resources Used 

**Python Version:** 3.7  
 
**Platforms:** Jupiter Notebooks
 
**Visualization Tools:** Microsoft Power BI

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, 
 
 



## Data Cleaning

We needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:



*  

*  

*  

*  



## EDA

We looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights. 



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
