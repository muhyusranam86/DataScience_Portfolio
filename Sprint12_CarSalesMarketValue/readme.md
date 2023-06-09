# Project description
Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. Historical data is available: technical specifications, trim versions, and prices.

## Project Goal:
Build the model to determine the market value of the cars. Rusty Bargain is interested in:
* The quality of the prediction
* The speed of the prediction
* The time required for training

### Model Training
* Trained different models with various hyperparameters. The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.
* Analyze the speed and quality of the models.
* Used the RMSE metric to evaluate the models.
* Use Linear regression for doing a sanity check of other methods.

### Data description
* `DateCrawled` — date profile was downloaded from the database
* `VehicleType` — vehicle body type
* `RegistrationYear` — vehicle registration year
* `Gearbox` — gearbox type
* `Power` — power (hp)
* `Model` — vehicle model
* `Mileage` — mileage (measured in km due to dataset's regional specifics)
* `RegistrationMonth` — vehicle registration month
* `FuelType` — fuel type
* `Brand` — vehicle brand
* `NotRepaired` — vehicle repaired or not
* `DateCreated` — date of profile creation
* `NumberOfPictures` — number of vehicle pictures
* `PostalCode` — postal code of profile owner (user)
* `LastSeen` — date of the last activity of the user

Target
* `Price` — price (Euro)

## Libraries Used
* Pandas
* Matplotlib.pyplot
* scipy.stats
* numpy
* time
* sklearn
* lightGBM
* catboost
* xgboost

## Models Evaluated
* LinearRegressor
* DecisionTreeRegressor
* RandomForestRegressor
* Ridge
* XGBRegressor
* LGBMRegressor
* CatBoostRegressor
