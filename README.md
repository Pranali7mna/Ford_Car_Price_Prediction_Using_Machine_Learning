🚗 Ford Car Price Prediction using Machine Learning
📌 Project Overview

This project predicts the selling price of Ford cars using Machine Learning. The dataset contains various features such as model, year, transmission type, mileage, fuel type, tax, MPG, and engine size. The project includes data preprocessing, exploratory data analysis (EDA), feature encoding, feature scaling, and model training using Linear Regression.

📂 Dataset Features
Model – Car model
Year – Manufacturing year
Transmission – Manual/Automatic/Semi-Auto
Mileage – Total distance driven
Fuel Type – Petrol/Diesel/Hybrid
Tax – Road tax
MPG – Miles per gallon
Engine Size – Engine capacity (L)
Price (Target Variable) – Selling price of the car
📊 Exploratory Data Analysis (EDA)

The following visualizations were performed:

Histogram of car prices
Correlation heatmap
Price distribution by manufacturing year
Mileage vs Price scatter plot
Engine Size vs Price
Transmission vs Price
Fuel Type vs Price
Model vs Price
Tax vs Price

⚙️ Data Preprocessing
Checked dataset information and missing values.
Performed One-Hot Encoding for categorical features.
Also experimented with Label Encoding for comparison.
Standardized numerical features using StandardScaler.
Split the dataset into training and testing sets (67% train, 33% test).


🤖 Machine Learning Model
Linear Regression


📈 Model Evaluation

The model performance was evaluated using:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)

Note: Update the README with your final R² Score, MAE, and MSE after training.

Example:

Model	R² Score
Linear Regression (One-Hot Encoding)	0.83%
Linear Regression (Label Encoding)	0.73%

🛠️ Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

📁 Project Workflow

Import libraries
Load dataset
Data exploration
Exploratory Data Analysis (EDA)
Feature encoding (One-Hot & Label Encoding)
Feature scaling
Train-test split
Train Linear Regression model
Evaluate model performance
Compare encoding techniques
