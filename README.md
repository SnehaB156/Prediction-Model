# Prediction-Model
# Diabetes Prediction Model

## Description
This project implements a logistic regression model to predict the risk of diabetes based on various health metrics. The model uses the Pima Indians Diabetes Database to train and evaluate its predictions.

## Features
- Loads and preprocesses the diabetes dataset.
- Implements feature scaling for better model performance.
- Trains a logistic regression model.
- Allows user input for real-time diabetes risk assessment.
- Provides accuracy metrics for the trained model.

## Dataset
The dataset is sourced from the [Pima Indians Diabetes Database](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv) and includes the following features:
- `Pregnancies`: Number of pregnancies
- `Glucose`: Plasma glucose concentration
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skin fold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0 or 1) indicating the presence of diabetes

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`

## Installation
Install the required libraries using pip:
```bash
pip install numpy pandas scikit-learn

## How to Use
The script will load the dataset and train a logistic regression model.
You will be prompted to enter the following health metrics:
Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
After entering the data, the model will predict whether the individual is diabetic (1) or non-diabetic (0).
You can repeat the input for multiple individuals.
