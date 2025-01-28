# CAR-PRICE-PREDICTION-MODEL

This project predicts the price of used cars based on various features such as brand, condition, kilometers driven, physical damage, and year of manufacture. The model is built using **Gradient Boosting Regressor** and is trained on a synthetic dataset.

## Project Overview

The goal of this project is to create a machine learning model that can predict the price of a car based on the following features:
- **Brand**: The brand of the car (e.g., Toyota, Honda, etc.)
- **Condition**: The condition of the car (e.g., New, Used, Damaged)
- **Kilometers Driven**: The total kilometers the car has been driven.
- **Physical Damage**: The extent of physical damage (e.g., None, Minor, Major).
- **Year**: The year the car was manufactured.

The model uses **Gradient Boosting Regressor** from the `sklearn` library to make predictions. Preprocessing is done using `StandardScaler` for numerical features and `OneHotEncoder` for categorical features.

Requirements-

- Python 3.x
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `joblib`

You can install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt

pandas
numpy
matplotlib
scikit-learn
joblib


Results
Root Mean Squared Error (RMSE): The model's performance is evaluated using RMSE. The lower the RMSE, the better the model's predictions.
Visualization: A scatter plot comparing actual vs. predicted car prices is displayed.


Model Evaluation
The model is evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
The scatter plot visualizes how well the model's predictions align with the actual prices.


File Descriptions
car_price_prediction.py: Main script that handles data loading, preprocessing, model training, and evaluation.
car_price_prediction_model.pkl: The trained model saved using joblib.
car_data.csv: Synthetic dataset used for training and testing (or you can replace it with an actual dataset).
