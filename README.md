The Smart Irrigation and Crop Price Prediction System is an AI-powered web application designed to assist farmers in making intelligent, data-driven agricultural decisions using machine learning and real-time weather data.
The system predicts irrigation requirements based on environmental conditions such as temperature, humidity, rainfall and soil moisture using a trained classification model and also forecasts crop prices using a regression model trained on historical agricultural datasets.
It integrates a Weather API to fetch live climate data, which is processed by ML models to generate accurate predictions.

The backend is built using Flask while the frontend provides a clean, interactive dashboard where user inputs are taken and AI-generated results are displayed in a structured and professional UI.
The project is organized into multiple files for modularity and easy maintenance.

The app.py file serves as the main backend application that runs the Flask server, handles routing, processes user requests, connects the frontend with machine learning models, fetches real-time weather data and returns predictions for irrigation and crop price.
The irrigation_model.py file is responsible for training the irrigation prediction model using agricultural datasets, applying machine learning algorithms, evaluating performance and generating a trained model that determines whether irrigation is required.
Similarly the price_model.py file handles the training of the crop price prediction model using historical market data and regression techniques to estimate future crop prices based on environmental conditions.
The index.html file defines the structure of the web interface, including input fields, layout design and sections for displaying results in a user-friendly dashboard format.
The style.css file is used to design a modern, responsive and professional UI with a clean layout that separates input and output panels for better user experience.

Together these components form a complete end-to-end AI system that demonstrates the application of machine learning in agriculture, helping optimize irrigation usage, predict market trends and support farmers in making efficient and informed decisions.
