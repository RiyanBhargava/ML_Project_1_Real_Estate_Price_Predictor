# Real Estate Price Predictor

Welcome to the Real Estate Price Predictor project! This repository contains everything you need to predict real estate prices using a machine learning model. The project includes a dataset, a machine learning model, a user interface built with HTML, CSS, and JavaScript, and a backend implemented with Flask.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Machine Learning Model](#machine-learning-model)
- [User Interface](#user-interface)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Real Estate Price Predictor is a tool designed to estimate the price of real estate properties based on various features. This project leverages machine learning to provide accurate predictions and offers a user-friendly interface for easy interaction.

## Features

- Predict real estate prices based on input features
- Simple and intuitive user interface
- Backend powered by Flask
- Linear Regression model for predictions
- Extensible codebase for experimenting with different models

## Dataset

The dataset used in this project includes various features related to real estate properties, such as location, total sqft size, number of rooms, and other relevant attributes. The dataset is preprocessed and ready for use in training and testing the machine learning model.

## Machine Learning Model

After testing various models, Linear Regression was found to be the best fit for this project. The model has been trained and tested to ensure accurate predictions.

## User Interface

The user interface is built with HTML, CSS, and JavaScript, providing an easy-to-use platform for users to input property details and receive price predictions. The UI communicates with the Flask backend to retrieve predictions.

## Installation

To get started with the Real Estate Price Predictor, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/RiyanBhargava/ML_Project_1_Real_Estate_Price_Predictor.git
   cd ML_Project_1_Real_Estate_Price_Predictor
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```bash
   flask run
   ```

5. Open your web browser and navigate to `http://127.0.0.1:5000` to use the application.

## Usage

1. Open the application in your web browser.
2. Enter the details of the property you want to predict the price for.
3. Click the "Predict" button to receive the estimated price.

## Contributing

Contributions are welcome! If you have any ideas or suggestions to improve this project, please open an issue or submit a pull request.

