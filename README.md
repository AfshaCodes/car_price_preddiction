# Car Price Prediction ML Project

This project implements a machine learning model to predict car prices based on features like brand, year, mileage, fuel type, and more. The project is divided into data preprocessing, model training, evaluation, and deployment via a Streamlit web app.

## Features
1. **Data Preprocessing**:
   - Handles missing values, encodes categorical data, and scales numeric features.
   - Splits data into training and testing sets.

2. **Model Training**:
   - Trains regression models to predict car prices.
   - Supports model evaluation with metrics like RMSE and R².

3. **Model Deployment**:
   - Deploys the trained model using Streamlit to provide a user-friendly interface for predictions.

## Prerequisites
- Python 3.x
- Libraries:
  - Data processing: `pandas`, `numpy`
  - Machine learning: `scikit-learn`
  - Visualization: `matplotlib`, `seaborn`
  - Deployment: `streamlit`

## How to Run

### Step 1: Setting up the Environment
1. Install Python 3.x.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn streamlit
