# Home_Price_Prediction-Linear-Regression-Analysis 

## Project Overview

This project uses multiple linear regression modeling to analyze house They are primarily interested in: what zipcodes have the lowest prices, predicted prices of homes in the area, and any relevant differences between the real prices and our model's predicted price.sales in a northwestern county.

## Business and Data Understanding

Jamii Real Estate wants to purchase homes in the Seattle area. They have tasked us with determining how much to spend on a home, on average, and areas to purchase homes in.

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




 ## Conclusion 
 Given how grade alone can influence the price of a house, homeowners should invest in the maintenance and repair worn out features such as paint, roofing in order to improve the overall condition of the house.

It's also observed that houses with better quality materials and better construction on general attracts high pricing to houses, it is therefore advisable for home owners with larger budgets to invest in design upgrades but then not to extreme ends as it can be seen from the analysis how grade_8_goodseems to have a higher effect than higher grade homes.







