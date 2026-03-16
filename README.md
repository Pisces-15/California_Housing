# California_Housing
🏠 California Housing Price Prediction System

A Machine Learning Web Application built using Python, XGBoost, and Streamlit that predicts the estimated price of houses in California based on housing and demographic data.

The application allows users to input various housing features such as median income, house age, number of rooms, population, and location coordinates to estimate the house price using a trained machine learning model.

🚀 Live Demo - https://californiahousing-ggtvfkre4rq3ccmgpsau2s.streamlit.app/

📌 Project Overview

This project demonstrates the end-to-end Machine Learning workflow, including:

Data preprocessing

Model training

Model serialization using Pickle

Deployment using Streamlit

Creating an interactive user interface for predictions

The model is trained on the California Housing dataset, which contains housing statistics collected from California districts.

🧠 Machine Learning Model

The model used in this project is:

XGBoost Regressor

XGBoost is a powerful gradient boosting algorithm known for:

High prediction accuracy

Fast training performance

Strong handling of structured data

The trained model is stored as a Pickle (.pkl) file and loaded into the Streamlit application for predictions.

📁 Project Structure
california-housing-price-prediction
│
├── app.py
├── california_housing.pkl
├── requirements.txt
└── README.md

🛠️ Technologies Used

Python

Streamlit

NumPy

Scikit-learn

XGBoost

Pickle

