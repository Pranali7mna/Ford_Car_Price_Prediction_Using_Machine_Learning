# 🚗 Ford Car Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of **Ford cars** using **Machine Learning**. The dataset contains various features such as model, year, transmission type, mileage, fuel type, tax, MPG, and engine size. The project includes data preprocessing, exploratory data analysis (EDA), feature encoding, feature scaling, and model training using **Linear Regression**.

---

## 📂 Dataset Features

* **Model** – Car model
* **Year** – Manufacturing year
* **Transmission** – Manual/Automatic/Semi-Auto
* **Mileage** – Total distance driven
* **Fuel Type** – Petrol/Diesel/Hybrid
* **Tax** – Road tax
* **MPG** – Miles per gallon
* **Engine Size** – Engine capacity (L)
* **Price** *(Target Variable)* – Selling price of the car

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were performed:

* Histogram of car prices
* Correlation heatmap
* Price distribution by manufacturing year
* Mileage vs Price scatter plot
* Engine Size vs Price
* Transmission vs Price
* Fuel Type vs Price
* Model vs Price
* Tax vs Price

---

## ⚙️ Data Preprocessing

* Checked dataset information and missing values.
* Performed **One-Hot Encoding** for categorical features.
* Also experimented with **Label Encoding** for comparison.
* Standardized numerical features using **StandardScaler**.
* Split the dataset into training and testing sets (67% train, 33% test).

---

## 🤖 Machine Learning Model

* **Linear Regression**

---

## 📈 Model Evaluation

The model performance was evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**

> **Note:** Update the README with your final **R² Score**, **MAE**, and **MSE** after training.

Example:

| Model                                |  R² Score |
| ------------------------------------ | --------: |
| Linear Regression (One-Hot Encoding) | **0.83%** |
| Linear Regression (Label Encoding)   | **0.73%** |

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Workflow

1. Import libraries
2. Load dataset
3. Data exploration
4. Exploratory Data Analysis (EDA)
5. Feature encoding (One-Hot & Label Encoding)
6. Feature scaling
7. Train-test split
8. Train Linear Regression model
9. Evaluate model performance
10. Compare encoding techniques

---

## 🚀 Key Highlights

* Performed complete data preprocessing and visualization.
* Compared **One-Hot Encoding** and **Label Encoding** for categorical variables.
* Applied feature scaling using **StandardScaler**.
* Built a **Linear Regression** model for price prediction.
* Evaluated the model using regression metrics.

---

### 📌 Future Improvements

* Try advanced regression models such as:

  * Random Forest Regressor
  * XGBoost Regressor
  * Gradient Boosting Regressor
  * Decision Tree Regressor
* Perform hyperparameter tuning.
* Build a Streamlit web application for real-time car price prediction.

---

## ⭐ If you found this project useful, consider giving it a star!
