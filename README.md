# Regression Models Machine Learning Project

This project demonstrates the implementation of multiple regression algorithms using Python and Scikit-Learn. The trained model is deployed using a Flask web application for predictions.

## Algorithms Implemented

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Matplotlib

## Project Structure

```
regression-ml-flask-deployment
│
├── data
│   └── dataset.csv
│
├── models
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── notebooks
│   ├── linear_regression.ipynb
│   └── regression_all_types.ipynb
│
├── templates
│   ├── index.html
│   └── home.html
│
├── app.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository

```bash
git clone (https://github.com/PriyankaMittha/regression-ml-flask-deployment)
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open in browser

```
http://127.0.0.1:5000
```

## Model Deployment

The trained Ridge Regression model is saved using pickle and loaded in the Flask application to make predictions based on user input.

## Features

- Data preprocessing
- Feature scaling using StandardScaler
- Model training
- Model evaluation
- Web interface for predictions

## Author

Priyanka Mittha
