# usedCarPrices

**Objective** : Predicting used car prices in India.

# Notebook

* View / Download the notebook [here](https://github.com/Gothamv/usedCarPrices/blob/master/predictingCarPrices.ipynb).
* Run the Notebook on Kaggle [here](https://www.kaggle.com/gothamv/predictingcarprices).

# Models used
* Linear Regression
* Random Forest Regression
* XGBoost Regression
* Ridge Regression
* Lasso Regression

# Dataset Features
* Name: The brand and model of the car.
* Location: The location in which the car is being sold or is available for purchase.
* Year: The year or edition of the model.
* Kilometers_Driven: The total kilometres driven in the car by the previous owner(s) in KM.
* Fuel_Type: The type of fuel used by the car.
* Transmission: The type of transmission used by the car.
* Owner_Type: Whether the ownership is Firsthand, Second hand or other.
* Mileage: The standard mileage offered by the car company in kmpl or km/kg
* Engine: The displacement volume of the engine in cc.
* Power: The maximum power of the engine in bhp.
* Seats: The number of seats in the car.
* Price: The price of the used car in INR Lakhs.

# File Description
* [Data_Train.csv](https://github.com/Gothamv/usedCarPrices/blob/master/Data_Train.csv) : Used for training
* [Data_Test.csv](https://github.com/Gothamv/usedCarPrices/blob/master/Data_Test.csv) : Used for making final predictions
* [predictions.csv](https://github.com/Gothamv/usedCarPrices/blob/master/predictions.csv) : Contains the predictions made by XGBoost Regressorr which had the best R2 score.
