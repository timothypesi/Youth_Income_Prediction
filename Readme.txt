# Predictive Insights Competition: Youth Employment Prediction

## Introduction
The project aims to tackle youth unemployment in South Africa. Using data from periodic labour market surveys, a machine learning model is developed to predict the employment status of the youth one year after the survey.

## Dataset
The dataset comprises survey data from South African youth, collected at 6-month intervals. It includes numerical, categorical, and textual inputs, alongside demographic details such as age and education.

## Installation
1. Clone this repository.
git clone [your-repository-link]

2. Navigate to the project directory and install the dependencies using pip.
cd [your-repository-name]
pip install -r requirements.txt

## Usage
1. To run the API locally:
python your_flask_script.py

This will start the Flask server on `http://127.0.0.1:5000`.

2. To make a prediction, send a POST request with the required data to `http://127.0.0.1:5000/predict`.

## Deployment
The application can be deployed using cloud providers like AWS, Google Cloud, or Heroku. For production, ensure the Flask application is run using a server like Gunicorn.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements
Thanks to Predictive Insights for the dataset and the challenge.
