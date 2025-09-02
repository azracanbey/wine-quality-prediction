# Wine Quality Prediction

This repository contains a project on predicting red wine quality using the [Wine Quality - Red](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) dataset from Kaggle.

## Dataset

The dataset includes 1,599 samples of red wine from the Vinho Verde region in Portugal. Each sample contains 11 physicochemical features (such as acidity, sugar, pH, and alcohol) and a quality score ranging from 0 to 10.

## Project Description

The goal of this project is to predict the quality of red wine based on its chemical properties. Several regression models have been implemented and evaluated:

- Decision Tree Regression
- Linear Regression
- Polynomial Regression
- Support Vector Regression (SVR)

The models' performances are evaluated using **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R² score**. Note that low R² values may occur due to the subjective nature of wine quality and the inherent variability in the dataset, and do not necessarily indicate a failure of the models.

## Results

For each model, a comparison plot of actual vs predicted quality values has been created. These visualizations help to understand how well each model captures trends in the dataset.

## How to Run

1. Clone the repository.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
