# Multi-Disease Risk Prediction & Preventive Advice

This project provides a **user-friendly system** to predict the risk of **Heart Disease, Diabetes, and Hypertension** using independent machine learning models. Each model is trained on its respective dataset using algorithms like **Random Forest and XGBoost** for accurate predictions.

## Features
- Predict **Heart Disease**, **Diabetes**, and **Hypertension** risks individually.
- Receive **risk categories**: Low, Moderate, or High.
- Get **personalized preventive advice** based on health parameters.
- Interactive **Gradio web interfaces** for each disease model.

## Project Structure

MultiDiseasePrediction/
│
├─ heart_model.pkl
├─ diabetes_model.pkl
├─ hypertension_model.pkl
│
├─ heart_app.py
├─ diabetes_app.py
├─ hypertension_app.py
│
├─ requirements.txt
└─ README.md

## Requirements
- Python 3.x  
- pandas  
- scikit-learn  
- Randomforest 
- gradio  
- joblib  

Install dependencies using:

```bash
pip install -r requirements.txt
