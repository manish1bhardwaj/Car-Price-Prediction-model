# Car-Price-Prediction-model
🚗 Car Price Prediction – A Machine Learning Approach


📄 Project Overview
In today’s dynamic automobile market, accurately predicting used car prices is crucial for both buyers and sellers. This project builds a machine learning model to predict the selling price of used cars using real-world attributes like brand, year, mileage, fuel type, transmission, owner type, and location.

🎯 Objective
Develop a predictive model that estimates a car's selling price, helping to make data-driven pricing decisions.

🗂️ Dataset
The dataset includes the following features:

Name: Car brand and model

Year: Year of manufacture

Selling price: Target variable (price in ₹)

Km driven: Total distance driven

Fuel type: Petrol, Diesel, CNG, LPG

Seller type: Dealer or individual

Transmission: Manual or automatic

Owner: Number of previous owners

Location: City (added in this project)

Mileage: Derived feature (based on year)

🔬 Exploratory Data Analysis (EDA) Insights
Newer cars have higher selling prices.

Lower mileage generally implies higher value.

Automatic transmission cars and cars with fewer owners tend to be priced higher.

Mumbai and Delhi show slightly higher average prices than other cities.

⚙️ Preprocessing Steps
Label Encoding for categorical features

Feature scaling using StandardScaler

Train-test split (80:20)

🤖 Modeling
Algorithm: Linear Regression

Metrics:

MAE: ₹221,710

MSE: ₹184,225,713,662

RMSE: ₹429,215

R² Score: 0.396

📈 Feature Importance (Coefficients)
Feature	Coefficient (₹)
Year	+78,312
Location	+3,724
Seller type	–10,664
Name	–14,153
Owner	–17,612
Km driven	–47,345
Mileage	–78,312
Fuel	–144,528
Transmission	–275,773

💡 Conclusions & Future Work
The model captures general price trends but has room for improvement.

Future enhancements:

Handle outliers

Use advanced regressors (Ridge, Lasso, Random Forest, Gradient Boosting)

Incorporate more features (e.g., service history, accident record)

Try polynomial or interaction terms to capture non-linear effects
