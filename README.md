# 🏡 Housing Price Prediction Using Linear Regression
This project demonstrates how to build a Linear Regression model in Python to predict house prices based on three core features: square footage, number of bedrooms, and number of bathrooms. The dataset used is synthetically generated to mimic real-world housing trends.

## 📌 Project Highlights
🔍 Objective
To develop and evaluate a Linear Regression model for predicting housing prices using clean, structured data and performance visualizations.

## ✅ Key Steps
### 🔢 Data Generation

Synthetic data is generated for:

SquareFootage: 500–4000 sq ft

Bedrooms: 1–5

Bathrooms: 1–3

Price is computed using a linear formula with added noise to simulate real-world variability.

### 🧹 Data Preparation

Data is stored in a pandas DataFrame.

Feature set (X) and target variable (y) are separated.

### 🧪 Train-Test Split

The dataset is split into training and testing sets using an 80/20 split via train_test_split.

### 🧠 Model Training

A LinearRegression model from scikit-learn is trained on the training data.

### 📈 Model Evaluation

Predictions are generated for the test set.

Model performance is evaluated using:

Mean Squared Error (MSE)

R-squared Score (R²)

### 📉 Visualization

A scatter plot displays actual vs. predicted prices.

A red dashed line represents the ideal prediction curve (perfect match).

## 🛠 Technologies Used
Python

pandas

NumPy

scikit-learn

matplotlib

seaborn
