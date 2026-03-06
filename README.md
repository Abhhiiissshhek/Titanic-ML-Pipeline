# Titanic ML Pipeline

## Overview
End-to-end ML pipeline built using scikit-learn.

This project includes:
- Data preprocessing
- Feature scaling
- Logistic Regression model
- Model saving using joblib
- Separate prediction script

## Project Structure

Titanic-ML-Pipeline/
│
├── data/
├── notebook/
├── src/
├── models/
├── requirements.txt
└── README.md

## How to Run

1. Create virtual environment:
   python -m venv venv

2. Activate:
   venv\Scripts\activate

3. Install dependencies:
   pip install -r requirements.txt

4. Train model:
   python src/train.py

5. Predict:
   python src/predict.py

## Model Accuracy
Add your accuracy here.

## Tech Stack
- Python
- scikit-learn
- pandas
- joblib