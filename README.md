<html>

<p align="left"><img width="1000" height="auto" src="Images/header.PNG"></p>          

<body>

<p>



<h2>Predicting the City-Cycle Fuel Consumption in Miles per Gallon of a Car</h2>

This Group Project was made during ReGeneration Academy on Data Science(powered by Papastratos) during September/October 2021.

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
 
 *  Type of Ownership 

*  Industry

*  Sector

*  Revenue

*  Competitors 



## Data Cleaning

After scraping the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:



*  Parsed numeric data out of salary 

*  Made columns for employer provided salary and hourly wages 

*  Made columns for if different skills were listed in the job description:

    * Python  

    * R  

 

*  Column for simplified job title and Seniority 

*  Column for description length 



## EDA

I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 



## Model Building 



First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.   



I tried three different models and evaluated them using Mean Absolute Error. I chose MAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.   



I tried three different models:

*  **Multiple Linear Regression** – Baseline for the model

*  **Lasso Regression** – Because of the sparse data from the many categorical variables, I thought a normalized regression like lasso would be effective.

*  **Random Forest** – Again, with the sparsity associated with the data, I thought that this would be a good fit. 



## Model performance

The Random Forest model far outperformed the other approaches on the test and validation sets. 

*  **Random Forest** : MAE = 11.22

*  **Linear Regression**: MAE = 18.86

*  **Ridge Regression**: MAE = 19.67



## Productionization 

In this step, I built a flask API endpoint that was hosted on a local webserver by following along with the TDS tutorial in the reference section above. The API endpoint takes in a request with a list of values from a job listing and returns an estimated salary. 
 
<br>
<br>
<p align="center"><kbd><img width="1000" height="100" src="Images/header.PNG"></kbd></p><br>                     
<br>
</body>
</html>
