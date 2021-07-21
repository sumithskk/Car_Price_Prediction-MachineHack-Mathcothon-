# Car_Price_Prediction-MachineHack-Mathcothon

## Overview
With the rise in the variety of cars with differentiated capabilities and features such as model, production year, category, brand, fuel type, engine volume, mileage, cylinders, colour, airbags and many more, we are bringing a car price prediction challenge for all. We all aspire to own a car within budget with the best features available. 

![car_price](https://user-images.githubusercontent.com/42634704/126543070-89eb0aa8-7eeb-4d59-9a3e-11f6e0288196.jpg)



## About Data

With the rise in the variety of cars with differentiated capabilities and features such as model, production year, category, brand, fuel type, engine volume, mileage, cylinders, colour, airbags and many more, we are bringing a car price prediction challenge for all. We all aspire to own a car within budget with the best features available. 

Train.csv - 19237 rows x 18 columns (Includes Price Columns as Target) 

Test.csv - 8245 rows x 17 columns

Attributes

          * ID
          * Price: price of the car(Target Column)
          * Levy
          * Manufacturer
          * Model
          * Prod. year
          * Category
          * Leather interior
          * Fuel type
          * Engine volume
          * Mileage
          * Cylinders
          * Gear box type
          * Drive wheels
          * Doors
          * Wheel
          * Color
          * Airbags



## Technical Aspect

 * Multivariate Regression
 * Big dataset, underfitting vs overfitting
 * Optimizing RMSLE to generalize well on unseen data

## Evaluation

* The submission will be evaluated using the RMSLE metric. One can use np.sqrt(mean_squared_log_error(actual, predicted)) to calculate the same
* This hackathon supports private and public leaderboards
* The public leaderboard is evaluated on 70% of Test data

## Credits

* This hackathon participation wouldn't have been possible without MachineHack. It helped a lot to learn by doing from this website.
https://machinehack.com/hackathons/data_hack_mathcothon_car_price_prediction_challenge/overview
* Thanks to Krish Naik, he helped a lot to learn from his youtube channel.
https://www.youtube.com/user/krishnaik06

