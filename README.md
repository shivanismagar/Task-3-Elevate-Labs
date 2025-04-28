House Price Prediction using Linear Regression
This project implements Simple and Multiple Linear Regression models to predict House Prices based on different features like area, number of bedrooms, bathrooms, parking availability, and more.

📚 Project Overview
Dataset: House price data with features like area, bedrooms, bathrooms, main road access, guestroom availability, etc.

Libraries Used:

pandas

numpy

matplotlib

scikit-learn

Approach:

Simple Linear Regression (using Area only)

Multiple Linear Regression (using multiple features)

 About the Steps
Import Libraries
Imported required libraries: pandas, numpy, matplotlib, and scikit-learn.

Load Dataset
Loaded the house price dataset using pandas.

Preprocessing

Dropped the furnishingstatus column (ignored as per instruction).

Encoded categorical variables (mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea) from 'yes'/'no' to 1/0.

Handled missing values by filling or dropping as needed.

Feature Selection

For Simple Linear Regression: Used only area.

For Multiple Linear Regression: Used features like area, bedrooms, bathrooms, stories, parking, and categorical fields.

Train-Test Split
Split the data into training and testing sets (80% training, 20% testing).

Model Training

Trained a Simple Linear Regression model using area.

Trained a Multiple Linear Regression model using all selected features.

Model Evaluation

Evaluated the models using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Visualization

Plotted the regression line over scatter plot for Simple Linear Regression (Area vs Price).

Interpretation

Printed and analyzed model coefficients and intercepts to understand the importance of each feature.


