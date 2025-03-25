House Rent Prediction :

[Prediction of  House Rent in Hyderabad]


Overview

This project aims to predict house rent using machine learning models trained on a dataset named hyd.csv. House rent prediction involves forecasting the rental price of residential properties using various data-driven techniques.The entire process, from data preprocessing to model training and deployment, is thoroughly documented and executed in a Jupyter notebook . The final model is deployed using a Flask backend, and the user interface is built with HTML, CSS, and JavaScript.


Data Preprocessing and Model Training

Dataset

The dataset used in this project is hyd.csv. This dataset contains various features to predict house rent.

Data Preprocessing

Dropping Columns: Unnecessary columns were dropped to streamline the dataset.
Feature Encoding: Categorical features in English were converted to numerical ranges to make them compatible with machine learning models.


Model Training

Multiple models from scikit-learn were trained and tested.
The models were evaluated based on their efficiency percentages.
The best-performing model was selected for deployment.
The chosen model's weights were trained and saved using joblib and pickle.


Notebook

All the preprocessing, training, and model dumping processes are documented in the Jupyter notebook untitled.ipynb.


Web Application

Backend

The backend is implemented using Flask.
It loads the trained model and handles incoming feature inputs from the frontend.
The inputs are converted into the correct data types and passed to the model for prediction.
The predicted house rent is  then displayed on another page.


Frontend

The frontend is built using HTML, CSS, and JavaScript.
The frontend web page consists of the details such as location, Type of BHK, floor, parking, property size, maintanence amount.
It displays the predicted rental price.
It prompts the user for feature inputs necessary for the prediction.

How to Run

bash
Copy code
pip install -r requirements.txt
Run the Flask application:

bash
Copy code
python app.py
Open the application:
Open your web browser and navigate to http://127.0.0.1:5000


Model Details


The required model is selected to predict the house rent
The frontend web page consists of the details such as location, Type of BHK, floor, parking, property size, maintanence amount.
These details must be entered by user to get the rental price for their requirement.
The rental price will be predicted .