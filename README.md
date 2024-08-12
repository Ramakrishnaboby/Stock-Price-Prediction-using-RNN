# Stock-Price-Prediction-using-RNN
## Overview
This project aims to predict stock prices using Recurrent Neural Networks (RNNs). The dataset includes historical stock data such as opening price, closing price, high, low, and volume for various companies. The RNN model is used to forecast future stock prices based on this historical data.

## Features
- Data Loading and Exploration:** Load and explore the dataset, including checking for unique values, number of records, and data types.
- Data Preprocessing:** Clean and prepare the data for modeling, including normalization and reshaping for time series analysis.
- RNN Model Implementation:** Build and train an RNN model using TensorFlow/Keras to predict stock prices.
- Model Evaluation:** Evaluate the model's performance using appropriate metrics and visualize the results.
- Visualization:** Generate plots to visualize the model's predictions against the actual stock prices.

## Dataset
The dataset contains the following columns:
- `date`: The date of the stock data entry.
- `symbol`: The ticker symbol of the stock.
- `open`: The opening price of the stock on that date.
- `close`: The closing price of the stock on that date.
- `low`: The lowest price of the stock on that date.
- `high`: The highest price of the stock on that date.
- `volume`: The trading volume of the stock on that date.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `tensorflow`
  - `keras`

### Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/stock-price-prediction-rnn.git
    ```
2. Navigate to the project directory:
    ```bash
    cd stock-price-prediction-rnn
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook
1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `Stock Price Prediction using RNN.ipynb` file.
3. Execute the cells sequentially to preprocess the data, build and train the model, and visualize the results.

## Model Architecture
The RNN model is built using Keras and consists of the following layers:
- LSTM Layer:** Long Short-Term Memory (LSTM) layer to capture temporal dependencies in the data.
- Dense Layer:** Fully connected layer to output the final stock price prediction.

## Results
The model's predictions are compared with the actual stock prices to evaluate its accuracy. Visualizations are generated to demonstrate the model's performance over time.

## Contributions
Contributions to improve the model or add new features are welcome. Please submit a pull request or create an issue to discuss your ideas.
