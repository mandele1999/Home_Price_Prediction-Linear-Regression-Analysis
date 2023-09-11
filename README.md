# Home_Price_Prediction-Linear-Regression-Analysis 
### Authors: James Maikara, Frank Mandele, Trevor Mwangi

## Project Overview

This project uses multiple linear regression modeling and iterative linear regression modeling to analyze house prices in relation to renovations. They are primarily interested in how renovations influence house pricing and models are created to provide estimates of prices which are then evaluated for fitness in our findings.

## Business and Data Understanding

A real estate agency wants to purchase homes in the Seattle area. They have tasked us with determining how much to spend on a home, on average, and areas to purchase homes in.

Our data set contains information of houses sold such as price, square footage and grade of the house. 

## Explain your stakeholder audience here

The stakeholder for this project is a commercial real estate company looking to purchase homes in a given area. They are primarily interested in: what houses have the lowest prices, predicted prices of homes in the area, and any relevant differences between the real prices and our model's predicted price. 

## Modeling
### Correlation Heatmap
![image](https://github.com/mandele1999/Home_Price_Prediction-Linear-Regression-Analysis/assets/133136216/d871521f-a5b6-4511-9c63-38085a9c1e04) 

## Prediction Models 
First Model was created using the strongest correlated continuous data feature then results interpreted.
Second model was for the grade features against the price

sqft_livingwas the attribute most strongly correlated with price, therefore our model is describing this relationship.
### First model 
Overall, this model is statistically significant with a p-value well below the standard alpha of 0.05 and it explains about 49.3% of the variance in price(*R-Squared*) i.e. coefficient of determination. In a typical prediction, the model is off by about $173k which is not very good.

The intercept is at about -43k dollars.This means that for zero sqft_living our model would predict a price of - 43k dollars. The coefficient for sqft_living is about 280 dollars. This means for each additional sqft, the sqft_living costs about $280 more.
Overall, this model is statistically significant with a p-value well below the standard alpha of 0.05 and it explains about 49.3% of the variance in price(*R-Squared*) i.e. coefficient of determination. In a typical prediction, the model is off by about $173k which is not very good.

The intercept is at about -43k dollars.This means that for zero sqft_living our model would predict a price of - 43k dollars. The coefficient for sqft_living is about 280 dollars. This means for each additional sqft, the sqft_living costs about $280 more.

### Second model
Overall the model performed marginally better. We were off by about $156k rather\nthan $173k in a given prediction, and explained 58.2% rather than 49.3% of the\nvariance in price.
###Comparison
![image](https://github.com/mandele1999/Home_Price_Prediction-Linear-Regression-Analysis/assets/133136216/4522c440-9914-4e44-8364-8f7e6031992a)
![image](https://github.com/mandele1999/Home_Price_Prediction-Linear-Regression-Analysis/assets/133136216/de3277f7-20cc-4e32-af3f-3e12d09a59f4)
From the two visualizations, model 2 has a higher R2 and lower mean squared error than the first model, which might be and indication of an improvement in our model



 ## Conclusion 
 From the analysis done, it is evident that property features accounted for in our input variables does indeed play a cruicial role in pricing of houses. Visualizations also indicate that better designs and better building materials demand relatively higher prices than average-standard setups. That said, it would be advisable for homeowners to take home maintenance through repairs of worn-out structures to ensure the property condition score is above average at least and investing more into design upgrades under advisement should they consider to sell / buy a house(s). Additional features such as having a waterfront seemed to attrach higher pricing for houses







