## House Price Prediction Model Repository Overview
This repository presents a House Price Prediction model crafted in Python, encompassing essential stages like data preprocessing, model building employing Ridge regression, and the integration of a web-based interface with Flask.

## Core Elements
# Data Cleaning: 
Employing a dataset sourced from Kaggle (Seattle House Price Prediction), the model undergoes meticulous data cleaning. This involves managing missing values, handling categorical data, and executing necessary preprocessing steps.

# Model Development: 
Utilizing Ridge regression through the scikit-learn library, the machine learning model is developed. It undergoes training and validation, with the resultant model being persisted for future usage.

# Flask Web Application: 
The project is furnished with a Flask-powered web application, facilitating an intuitive interface for predicting house prices. End-users can input pertinent details such as bedroom count, bathroom count, house size, and zip code to obtain a tailored price prediction.


#Usage:

1. Clone the repository:

git clone https://github.com/sm-sourabh/HousePrice_Prediction
cd HousePrice_Prediction

2. Install dependencies:

pip install -r requirements.txt

3. Run the Flask application:

python main.py

Open your web browser and visit http://127.0.0.1:5000/ to interact with the House Price Prediction interface.

# Datasets Used
Seattle House Price Prediction Dataset [Kaggle]
Feel free to explore and adapt the project for your own use. If you have any questions or suggestions, please create an issue or reach out to yourusername. Happy coding!
