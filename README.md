# Avocado Price Prediction
Noura Alhammad

# Abstract
The purpose of this project is to build a model to help avocado lovers to predict the future price of avocado-based on the product number and assign if the avocado is conventional or organic. 

First, I applied a pairplot to measure the relations between features. 
Then, I applied a correlation between each type of labeled avocado and the total volume of avocado.
Using a Linear regression for numerical prediction and Random Forest, then evaluated each model.

# Design
Reviews the avocado prices in detail, it presents to the people who love avocado and make it easier for them to enjoy with cheap avocados.

# Data
The dataset contains 18249 observations on 14 variables. the numerical column names refer to price lookup codes. 
1.	Small Hass.
2.	Large Hass.	
3.	Extra-large Hass

Features:

Date - The date of the observation.

AveragePrice - the average price of a single avocado.

type - Conventional or organic

year - The year.

region - the city or region of the observation.

Total Volume - Total number of avocados sold.

4046 - Total number of avocados with PLU 4046 sold.

4225 - Total number of avocados with PLU 4225 sold.

4770	- Total number of avocados with PLU 4770 sold.


# Algorithm
Model Used: Linear Regression, Random Forest Regressor, XGB Regressor.

# Tools
- Numpy and Pandas for data processing.
- Scikit-learn for modeling.
- Matplotlib and Seaborn for visualization.

# Communication
The presentation shows that geography influences the price, and organic is more expensive than conventional.
![image](https://user-images.githubusercontent.com/94787761/146292778-5c2f8fc4-30e7-46f3-95f9-c212273324f1.png)

![image](https://user-images.githubusercontent.com/94787761/146292793-2fffe9a1-e1d8-4b01-99cc-2435d4352fa7.png)
