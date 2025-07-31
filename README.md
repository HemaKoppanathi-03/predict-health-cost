# 🩺 Linear Regression Health Costs Calculator

This project is part of the [freeCodeCamp Machine Learning with Python certification](https://www.freecodecamp.org/learn/machine-learning-with-python/). The goal is to build a machine learning model that predicts healthcare expenses using patient data.

## 📊 Problem Statement

Given a dataset of personal attributes (age, sex, BMI, number of children, smoking status, and region), the objective is to predict medical insurance costs. The model should achieve a Mean Absolute Error (MAE) under **$3500** on unseen data to pass the challenge.

## 🔍 Dataset

The dataset is provided by freeCodeCamp and includes:

- `age`: Age of primary beneficiary
- `sex`: Gender
- `bmi`: Body mass index
- `children`: Number of dependents covered
- `smoker`: Smoking status
- `region`: Residential area in the US
- `expenses`: Medical insurance charges (target variable)

Data Source: [`insurance.csv`](https://cdn.freecodecamp.org/project-data/health-costs/insurance.csv)

## 🧠 Model Overview

- **Type:** Linear Regression (with deep learning layers)
- **Framework:** TensorFlow / Keras
- **Preprocessing:**
  - Categorical encoding using `pd.get_dummies`
  - Train-test split (80/20)
  - Feature normalization using `z-score`
- **Model Architecture:**
  - Input Layer
  - Two Hidden Layers (64 units, ReLU)
  - Output Layer (1 unit for regression)
- **Loss Function:** Mean Squared Error
- **Optimizer:** Adam

## 🚀 How to Run

1. Open the [Google Colab Notebook](#) (replace `#` with your shared link).
2. Run all cells in order.
3. The final cell will test the model and plot predictions.
4. To pass, MAE must be under `$3500`.

## ✅ Project Output

- Achieved a Mean Absolute Error under `$3500`, meeting the challenge criteria.
- Su
