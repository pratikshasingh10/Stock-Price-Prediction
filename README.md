# LSTM Model for Stock Price Prediction
This project demonstrates the use of Long Short-Term Memory (LSTM) networks for predicting stock prices. The notebook fetches stock data, preprocesses it, and trains an LSTM model to make predictions.

## Table of Contents
 - Installation
 - Usage
 - Project Structure
 - Results

## Installation
To run the notebook, you'll need to install the required Python packages. You can do this by running:

```bash
pip install -r requirements.txt
```
### Ensure you have the following packages installed:

 - pandas
 - numpy
 - matplotlib
 - yfinance
 - pandas_datareader
 - tensorflow
## Usage
### Clone the repository:
```bash

git clone https://github.com/pratikshasingh10/Stock-Price-Prediction.git
cd Stock-Price-Prediction
```
### Run the Jupyter notebook:
```bash
jupyter notebook "LSTM Model(AAPL).ipynb"
```
Follow the steps in the notebook to fetch stock data, preprocess it, and train the LSTM model.
## Project Structure
1. LSTM Model.ipynb: The main notebook containing all the steps for data fetching, preprocessing, model training, and prediction.
2. requirements.txt: A file listing all the dependencies required to run the notebook.
### Notebook Breakdown
1. Data Import and Preparation: <br>

 - Import necessary libraries.
 - Fetch stock data using the yfinance library.
 - Preprocess the data (e.g., removing unnecessary columns, normalizing data).
2. Model Building and Training: <br>

 - Build an LSTM model using TensorFlow/Keras.
 - Train the model on the prepared data.
### Prediction and Visualization:

1. Use the trained model to make predictions. <br>
2. Visualize the predictions alongside the actual stock prices. <br>
## Results
The notebook includes visualizations that compare the predicted stock prices with the actual prices, helping to evaluate the model's performance.
