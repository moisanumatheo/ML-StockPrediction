Stock Price Prediction

This project implements a stock price prediction model for the S&P 500 using Machine Learning algorithms in a Python Notebook. The goal is to forecast the closing price for the next day and generate predictions for the next 15 days.

Features

Data Loading – Uses historical prices of the S&P 500 index.
Preprocessing – Adds technical indicators such as moving averages and volatility.
Model Training – Implements XGBoost and Random Forest for predictions.
Evaluation – Measures model performance using RMSE and R² Score.
Visualization – Generates graphs comparing predictions with actual values.
Future Predictions – Estimates prices for the next 15 days and saves them in a CSV file.

Installation

Clone this repository:

git clone https://github.com/your-username/ML-StockPrediction.git
cd Stock_Prediction

Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt

Usage

Ensure you have the dataset (sp500.csv) inside the data/ folder.
Run the Jupyter Notebook to train the model and generate predictions.
The results, including future predictions, are saved in data/predictions_15_days.csv.

Results

The model provides accurate stock price forecasts.
Future predictions are visualized in graphs.



