# Project Description
Rusty Bargain is a used car sales service developing an app to attract new customers. With this app, you can quickly find out the market value of your car. You have access to the history, technical specifications, trim levels, and prices. You need to create a model that determines the market value.

## Rusty Bargain is interested in:

Prediction quality
Prediction speed
Training time

## Project Instructions
Download and examine the data.
Train different models with various hyperparameters (you should create at least two different models, but more is better. Remember, multiple gradient boosting implementations do not count as different models). The main goal of this step is to compare gradient boosting methods with random forests, decision trees, and linear regression.
Analyze the speed and quality of the models.

## Remarks:

- Use the RECM metric to evaluate models.
- Linear regression isn't very good for hyperparameter tuning, but it's perfect for sanity testing other methods. If gradient boosting performs worse than linear regression, something definitely went wrong.
- Use the LightGBM library and its tools to create gradient boosting models.
- Ideally, your project should have linear regression for sanity testing, a tree-based algorithm with hyperparameter tuning (preferably Random Forest), LightGBM with hyperparameter tuning (test a couple of ensembles), and CatBoost and XGBoost with hyperparameter tuning (optional).
- You can use a special command to find the execution time of cell code in Jupyter Notebook.
- Since training a gradient boosting model can take a long time, change only a few model parameters.

## Data Description
The dataset is stored in the file car_data.csv.

Features:

DateCrawled — date the profile was downloaded from the database
VehicleType — vehicle body type
RegistrationYear — vehicle registration year
Gearbox — gearbox type
Power — power (hp)
Model — vehicle model
Mileage — mileage (measured in km according to the regional specifics of the dataset)
RegistrationMonth — vehicle registration month
FuelType — fuel type
Brand — vehicle brand
NotRepaired — vehicle with or without repair
DateCreated — profile creation date
NumberOfPictures — number of vehicle photos
PostalCode — profile owner's (user's) postal code
LastSeen — date the user was last active

Goal:

Price — price (in euros)
