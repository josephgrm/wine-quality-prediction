# Wine Quality Prediction Project

## Overview
This repository contains a supervised machine learning project completed as my final assignment for the course Introduction to Machine Learning (CSCA 5622) in the Master’s program in Computer Science at the University of Colorado Boulder. The project is focused on predicting wine quality based on physicochemical properties. The project uses the UCI Wine Quality Dataset to demonstrates the complete machine learning workflow from data exploration to model evaluation.

## Project Overview
The dataset used is the Wine Quality dataset from the UCI Machine Learning Repository. It contains physicochemical properties of red and white variants of the Portuguese "Vinho Verde" wine, along with quality ratings.

### Features include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Project Structure
wine-quality-prediction/
│
├── data/                      # Store raw and processed data
│   ├── raw/                   # Original, immutable data
│   └── processed/             # Cleaned, transformed data
│
├── notebooks/                 # Jupyter notebooks
│   ├── 01_data_exploration.ipynb  # Initial EDA
│   └── 02_modeling.ipynb      # Model building and evaluation
│
├── models/                    # Saved model files
│
├── reports/                   # Generated reports
│   ├── figures/               # Generated graphics and figures
│   └── final_report.ipynb     # Final compiled notebook for submission
│
├── requirements.txt           # Project dependencies
└── README.md                  # Project description

## Key Findings
- We've successfully built a wine quality prediction model using Random Forest.
- After hyperparameter tuning, the model achieved an F1 score of 0.7222 on the test set.
- The most important features for predicting wine quality are:
   - alcohol
   - sulphates
   - volatile acidity
- These findings align with wine chemistry, where alcohol content, acidity levels,
   and preservatives like sulphates play crucial roles in wine quality.
- This model could help winemakers focus on the most influential factors
   during production to improve wine quality.

## Models Evaluated
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Acknowledgements
- UCI Machine Learning Repository for providing the dataset
- P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.