Stovekraft AI/ML Use Cases
Project Overview:

This repository contains the implementation of AI/ML solutions for various business problems at Stovekraft. The goal is to optimize operational efficiency, improve customer service, and enhance predictive capabilities. The solutions cover three major use cases:

Demand Forecasting, 

Predictive Maintenance,

Customer Service Chatbot.


Use Cases Overview:

1. Demand Forecasting:

Demand forecasting aims to predict future product demand based on historical sales data. This will help Stovekraft optimize inventory, production, and distribution strategies.

Key Techniques Used: Time-series models (ARIMA, Prophet, LSTM)

Data: Historical sales data, seasonality patterns

Output: Future demand predictions for products

2. Predictive Maintenance:

The predictive maintenance solution predicts the likelihood of equipment failures, reducing downtime and maintenance costs.

Key Techniques Used: Classification models (Random Forest, XGBoost), time-series analysis

Data: Sensor data, maintenance logs

Output: Maintenance schedules, failure predictions

3. Customer Service Chatbot:

The chatbot solution automates customer interactions, providing quick answers to frequently asked questions and handling common service queries.

Key Techniques Used: Natural Language Processing (NLP), intent classification (BERT, GPT)

Data: Historical customer interactions, conversation logs

Output: AI-powered chatbot for customer queries

Directory Structure:

Feasibility Report.md: Detailed feasibility analysis for each use case.

Demand_Forecasting/: Contains all files related to the demand forecasting model.

data/: Raw and processed data used for demand forecasting.

notebooks/: Jupyter notebooks for model training and evaluation.

models/: Saved models (e.g., pickle files) after training.

scripts/: Python scripts for preprocessing, training, and making predictions.

Predictive_Maintenance/: Contains all files related to the predictive maintenance model.

data/: Raw and processed data used for predictive maintenance.

notebooks/: Jupyter notebooks for model training and evaluation.

models/: Saved models (e.g., pickle files) after training.

scripts/: Python scripts for data preprocessing and model predictions.

Customer_Service_Chatbot/: Contains all files related to the chatbot development.

data/: Datasets used for training the chatbot.

notebooks/: Jupyter notebooks for chatbot implementation and evaluation.

models/: Pre-trained chatbot models.

scripts/: Python scripts for building the chatbot's conversational abilities.

