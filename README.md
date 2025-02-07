🚗 Car Price Prediction using Linear Regression

📌 Project Overview

This project builds a Car Price Prediction model using Linear Regression. The goal is to predict the price of a car based on various features like brand, year, engine size, fuel type, mileage, and more.

📊 Dataset

The dataset contains the following features:

Brand: Car manufacturer

Model: Specific model of the car

Year: Manufacturing year

Engine_Size: Engine capacity in liters

Fuel_Type: Type of fuel (Petrol, Diesel, etc.)

Transmission: Manual or Automatic

Mileage: Total distance traveled (in km/miles)

Doors: Number of doors

Owner_Count: Number of previous owners

Price: Target variable (Car price in USD)

🔧 Technologies Used

Python

Pandas (for data handling)

NumPy (for numerical computations)

Matplotlib & Seaborn (for data visualization)

Scikit-learn (for model training & evaluation)

🏗 Model Development

1. Data Preprocessing

Handle missing values

Encode categorical variables using One-Hot Encoding

Scale numerical features using StandardScaler

2. Model Training

Split data into train (80%) and test (20%)

Train a Linear Regression model using Scikit-learn

3. Model Evaluation

Mean Absolute Error (MAE): 20.00

Mean Squared Error (MSE): 4213.92

Root Mean Squared Error (RMSE): 64.91

R² Score: 0.9995

📈 Results & Insights

The model performed exceptionally well, with an R² score of 0.9995, meaning it explains 99.95% of the variance in car prices.

Low error metrics indicate high accuracy.

Possible overfitting due to the extremely high R² score, requiring further validation on unseen data.

🚀 Next Steps

Test on new/real-world data to check generalization

Experiment with other ML models (Random Forest, XGBoost)

Perform feature selection to improve interpretability




