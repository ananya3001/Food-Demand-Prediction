# Mini Project on Food Demand Prediction using ML
Contributer: Ananya Srivastava

## About
Demand forecasting is a key component to every growing online business. Without proper demand forecasting processes in place,it can be nearly impossible to have the right amount of stock on hand at any given time. A food delivery service has to dealwith a lot of perishable raw materials which makes it all the more important for such a company to accurately forecast daily and weekly demand.

Too much invertory in the warehouse means more risk of wastage,and not enough could lead to out-of-stocks - and push customers to seek solutions from your competitors. In this challenge, get a taste of demand forecasting challenge using a real datasets.

Thus this project uses Machine Learning to predict the orders for particular cuisine.

## Problem Statement
Your client is a meal delivery company which operates in multiple cities.They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly. The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable,the procurement planning is of utmost importance.Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful.Given the following information,the task is to predict the demand for the next 10 weeks(Weeks: 146-155) for the center-meal combinations in the test set:

1. Historical data of demand for a product-center combination(Weeks:1 to 145)
2. Product(Meal) features such as category,sub-category,current price and discount
3. Information for fulfillment center like center area, city information etc.

## Datasets Used
1. train.csv: Contains the historical demand data for all centers, test.csv contains all the following features except the target variable.
2. fullfilment_center_info.csv: Information regarding fullfilment centers.
3. meal_info.csv: Contains information regarding meals.

Food_Prediction.ipynb trains the model and saves the model.
FoodDemand.ipynb file needs to be executed to get the result as this contains the Demand prediction code.

Submitted to Digipodium 
1. http://www.digipodium.com/
2. http://github.com/digipodium
