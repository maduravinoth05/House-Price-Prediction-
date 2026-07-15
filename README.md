# 🏠 House Price Prediction using Artificial Intelligence  
CodTech IT Solutions — Python Programming Internship  
Task name : House Price Prediction  
Intern :   VINOTH.V  
Intern ID : CITS7154  
Domain : Artificial Intelligence  
Duration : 4 Weeks  
Internship Period : 16 July 2026 - 13 August 2026  

**Online Internship Project — Artificial Intelligence Course**

A supervised Machine Learning (AI) project that predicts house prices based
on property features such as area, number of bedrooms/bathrooms, number of
stories, age of the property, locality score, and parking spaces.

---

## 📌 Project Overview

This project applies **Artificial Intelligence / Machine Learning**
concepts to a real-world regression problem: predicting the price of a
house from its characteristics. It demonstrates the full AI project
pipeline — data generation/preprocessing, model training, evaluation, and
inference on new data.

Two supervised learning algorithms are implemented and compared:

- **Linear Regression** — a simple, interpretable statistical/AI model that
  assumes a linear relationship between input features and price
- **Random Forest Regressor** — an ensemble-based AI model made up of many
  decision trees, capable of learning non-linear patterns

---

## 🧠 AI Concepts Demonstrated

| Concept                     | Where it's used                                    |
|------------------------------|-----------------------------------------------------|
| Supervised Learning           | Model learns from labeled data (features → price)  |
| Regression                    | Predicting a continuous numeric value (price)       |
| Feature Scaling                | StandardScaler used before Linear Regression        |
| Ensemble Learning              | Random Forest combines multiple decision trees      |
| Train/Test Split               | Evaluating generalization on unseen data            |
| Model Evaluation Metrics       | MAE, RMSE, R² Score                                 |
| Inference / Prediction         | Using the trained model on a brand-new house        |

---

## 🎯 Objectives

- Understand how AI models learn from data
- Preprocess and prepare data for training
- Train and evaluate multiple AI regression models
- Compare model performance using standard metrics
- Use the trained AI model to predict the price of a new house

---

## 🛠️ Tech Stack

| Component        | Technology                        |
|--------------------|-------------------------------------|
| Language            | Python 3                            |
| Data Handling       | Pandas, NumPy                       |
| AI / ML Library     | scikit-learn                        |
| Algorithms          | Linear Regression, Random Forest    |
| Model Evaluation    | MAE, RMSE, R² Score                 |

---

## 📁 Project Structure

```
house-price-prediction-ai/
│
├── house_price_prediction.py   # Main AI program (data, training, evaluation, prediction)
├── sample_output.txt           # Sample console output
├── terminal_screenshot.png     # Screenshot of program execution
└── README.md                   # Project documentation
```

---

## 📊 Dataset

The program uses a **synthetically generated dataset** of 500 houses with
the following features:

| Feature           | Description                                 |
|--------------------|-----------------------------------------------|
| Area_sqft          | Built-up area in square feet                  |
| Bedrooms           | Number of bedrooms                            |
| Bathrooms          | Number of bathrooms                           |
| Stories            | Number of floors                              |
| Age_years          | Age of the house in years                     |
| Locality_Score     | Locality rating from 1 (low) to 10 (prime)     |
| Parking_Spaces     | Number of parking spaces                      |
| **Price**          | Target variable — house price (₹)             |

> For an actual AI course submission, you can replace `generate_dataset()`
> in the script with `pd.read_csv("house_data.csv")` to train on a real
> housing dataset (e.g. the Boston Housing or Kaggle House Prices dataset).

---

## ⚙️ How to Run

1. **Clone / download** the project folder.

2. **Install dependencies**
   ```bash
   pip install numpy pandas scikit-learn
   ```

3. **Run the program**
   ```bash
   python3 house_price_prediction.py
   ```

4. The AI program will:
   - Generate/load the dataset
   - Train Linear Regression and Random Forest AI models
   - Print evaluation metrics (MAE, RMSE, R²)
   - Show sample predictions vs actual prices
   - Predict the price for a new, unseen house

---

---

## 📐 Evaluation Metrics Used

- **MAE (Mean Absolute Error)** — average absolute difference between
  predicted and actual prices
- **RMSE (Root Mean Squared Error)** — penalizes larger errors more heavily,
  useful for spotting big mistakes
- **R² Score** — proportion of variance in price explained by the AI model
  (closer to 1 is better)

---

## 🚀 Future Improvements

- Use a real-world dataset (e.g. Kaggle's House Prices dataset)
- Add an Artificial Neural Network (ANN) model using TensorFlow/Keras
- Add feature engineering (e.g. price per sq. ft., distance from city center)
- Hyperparameter tuning with GridSearchCV
- Deploy the AI model using Flask/Streamlit as a web app
- Add k-fold cross-validation for more robust evaluation

---
