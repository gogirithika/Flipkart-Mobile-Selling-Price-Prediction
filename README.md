# Flipkart Mobile Selling Price Prediction

## Project Overview

This project focuses on predicting the selling price of mobile phones using Machine Learning techniques.

The model uses mobile phone features such as Original Price, Rating, Memory, and Storage to predict the Selling Price.

## Objective

The main objective of this project is to build a machine learning model that can predict the selling price of a mobile phone based on its features.

## Dataset

The dataset contains information about mobile phones and their prices.

### Important Features

- Original Price
- Rating
- Memory
- Storage
- Selling Price – Target Variable

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Understand the dataset
4. Check missing values
5. Check duplicate values
6. Perform data cleaning
7. Perform exploratory data analysis
8. Select relevant features
9. Split the data into training and testing sets
10. Build Machine Learning models
11. Evaluate model performance
12. Compare model results

## Machine Learning Models

The following regression techniques were explored:

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression

## Model Evaluation

The models were evaluated using:

- R² Score
- RMSE
- Cross-Validation Score

The Multiple Linear Regression model achieved approximately **0.95 R² score on the test dataset** in the evaluation.

## Key Insights

- Mobile selling price is influenced by features such as original price, rating, memory, and storage.
- Regression models can be used to estimate mobile selling prices based on available product features.
- Model performance was compared using multiple evaluation metrics.

## Project Structure

```text
Flipkart-Mobile-Selling-Price-Prediction
│
├── README.md
├── Mobile_Price_Prediction.ipynb
└── Flipkart_Mobile_Price.csv
##Conclusion

This project demonstrates the complete Machine Learning workflow, from data preprocessing and exploratory data analysis to model building and evaluation.

The project helped in understanding how regression algorithms can be applied to real-world price prediction problems.
