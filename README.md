# Cost-Prediction-for-Logistic-Company

Data Source: https://www.kaggle.com/competitions/cost-prediction-for-logistic-company-ml/

## Overview

   The logistics side of a company consists of different components such as : warehousing, packaging, inventory, transportation, and information. It is important for a company to be able to predict the cost of transporting their packages from point A to point B in order for them to have a clear idea of how much they should expect to spend on transportation costs. As an accounting student, I wanted to marry my knowledge in accounting and data science by focusing on the transportation component and create a model that predicts the transportation cost based on different variables. The data that I used came from Kaggle. This dataset, although it does not consist of "real" business data was still useful in creating a predictive model. It contained 11 different variables and roughly 40,000 rows of data. I ran different models such as: linear regression, grid search, and random forest. I ended up using a random forest model, a supervised machine learning algorith, to make this predictive model. The results of this model indicated that the weight, time of day, and origin location / destination location variables were the most correlated variables with cost (the variable we want to predict). Based off of these results my recommendations would be that the company optimize time of day, optimize origin location / destination location, and although reducing the weight of each transportation seems like commom sense, it is important to not diminish its impact on transporation costs.
   
## Business Problem

   The business problem that I am aiming to help solve is creating a model that predicts the transportation cost based off of different variables. The internal stakeholders are the business owner and CFO. A pain point related to this project is deciding if I should drop or keep the outliers in this dataset. My deliverable is both the analysis of the models results and the model itself. The way to approach the business problem is run regression models on the data set in order to see the relationship between the independent and dependent variables. 

## Data Understanding

- Where did the data come from?
    - Logistic company data from Kaggle
- What variables are included?
    - trip - Trip id
    - date - Date, when trip was made
    - dayPart - Day or Night
    - exWeatherTag - Heat / Snow
    - originLocation - Source location
    - destinationLocation - Destination location
    - distance - distance traveled
    - type - Expedited or Not
    - weight - weight carried by carriers
    - packageType - Type of packages
    - carrier - Name of the carriers
    - cost - transportation cost
- What is the target variable?
    - cost 
- What are the properties of the variables you intend to use?
    - trip
    - date
    - dayPart
    - originLocation
    - destinationLocation
    - distance
    - weight
    - cost
- Assumptions made on dataset 
    - cost variable is in thousands of dollars 
    - weight variable is in tons 
    
## Conclusion

- What would you recommend the business do as a result of this work?
    - Optimizing time of day
    - Optimizing origin & destination location 
    - Shipments with least weight 
- What are some reasons why your analysis might not fully solve the business problem?
    - Outliers in data 
- What else could you do in the future to improve this project (future work)?
    - Dealing with outliers
    - Predicting costs for each month
    - Expected freight cost in a year