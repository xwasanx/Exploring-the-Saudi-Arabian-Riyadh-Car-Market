# Exploring-the-Saudi-Arabian-Riyadh-Car-Market

## Dataset
The dataset used in this analysis is named "carsclean.csv" and is assumed to be located in the user's desktop directory (C:\Users\hp\Desktop\carsclean.csv). The dataset contains the following columns:

- `city`: The city where the car is listed (in this case, 'Al Riyadh')
- `car_maker`: The manufacturer of the car
- `model`: The model of the car
- `year`: The year the car was manufactured
- `condition`: The condition of the car (e.g., 'Used')
- `kilometers`: The number of kilometers the car has driven
- `transmission`: The type of transmission (e.g., 'Automatic')
- `fuel`: The type of fuel the car uses (e.g., 'Gasoline')
- `color`: The color of the car
- `pay_method`: The payment method accepted for the car (e.g., 'Cash Only', 'Cash or Installments')
- `price`: The listed price of the car

## Analysis
The notebook performs the following tasks:

1. Imports the necessary libraries (pandas, matplotlib, statsmodels, and scikit-learn).
2. Reads the "carsclean.csv" dataset into a pandas DataFrame named `cars`.
3. Displays the first 5 rows of the `cars` DataFrame using the `head()` method.
4. Checks for any missing values in the dataset.

The analysis can be expanded further to include:
- Exploratory data analysis (EDA) to understand the characteristics of the car market in Riyadh
- Visualizations to gain insights into the data
- Modeling and prediction of car prices based on the available features

## Requirements
This notebook requires the following Python libraries:
- pandas
- matplotlib
- statsmodels
- scikit-learn
