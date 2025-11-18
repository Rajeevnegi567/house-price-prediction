Project Structure




House-price-predication/
│
├── data/
│   ├── train_data.xlsx
│   ├── test_data.xlsx
│
├── model/
│   └── champion_model.joblib
│
├── notebooks/
│   └── house-price-prediction.ipynb
│
├── scripts/
│   └── house-price-prediction.py
│
├── outputs/
│   ├── houseprice_predictions_test.xlsx
│   └── test_metrics.json
│

Project Overview

This project uses Machine Learning Regression techniques to predict house prices based on features such as:

Size (sq ft)

Bedrooms

Bathrooms

Location

Age of house
…and more.

Both train and test datasets are included, and the project follows a clear ML pipeline:
✔ Data Cleaning
✔ Feature Engineering
✔ Exploratory Data Analysis
✔ Model Training
✔ Model Evaluation
✔ Saving & Loading Models
✔ Generating Predictions

Features Implemented
✔ 1. Train/Test Split

Training data and test data are stored separately in:

data/train_data.xlsx
data/test_data.xlsx

✔ 2. Model Training

The model is trained using algorithms such as:

Linear Regression

RandomForestRegressor

Gradient Boosting

The best-performing model is saved as:

model/champion_model.joblib

✔ 3. Predictions

Predictions for test data are generated and saved in:

outputs/houseprice_predictions_test.xlsx

✔ 4. Evaluation Metrics

Model performance metrics (MAE, RMSE, R² score) are saved in:

outputs/test_metrics.json

Technologies Used
Tool/Library	Purpose
Python	Core programming
Pandas	Data handling
NumPy	Numerical operations
Matplotlib / Seaborn	Visualization
Scikit-Learn	ML modeling
Joblib	Saving model
Jupyter Notebook	Code + explanation
