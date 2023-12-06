# Stock-Tracker


## Overview
The stock market is an ever-changing (dynamic) environment whose movements and fluctuations are affected by many factors such as news, previous prices and several other factors. As news and previous prices are considered one of the most important factors influencing the market and we want to measure the extent of the news’s impact on prices, predict the next price based on previous prices using deep learning techniques to help market analysts detect fraud or insider trading.


## Table of Contents
- [Requirements](#Requirements)
- [Installation](#installation)
- [Usage](#Usage)
- [Data](#Data)
- [Models](#Models)
- [Results](#Results)
- [Contributing](#Contributing)
- [License](#License)

## Requirements

- Python 3.9 or higher

## Installation


```bash
#pip install ta
#pip install TA-Lib

```

## Usage

To use the stock tracker project, follow these steps:

1. Prepare the data: Ensure that you have historical stock price data in a compatible format. You may need to preprocess the data or convert it into a specific format before training the models.

2. Train the models: Run the training script to train the LSTM and GRU models on your historical stock price data. Adjust the hyperparameters and model architecture as needed.

3. Make predictions: Use the trained models to make predictions on new or unseen data. This can be done by running the prediction script and providing the necessary inputs.

4. Evaluate the models: Assess the performance of the models by comparing the predicted closing prices with the actual prices. Calculate evaluation metrics : mean absolute error (MAE).

## Data

Collected from Saudi Exchange

## Models

The stock tracker project employs LSTM and GRU models for predicting stock closing prices. These models are well-suited for capturing temporal dependencies and patterns in sequential data.

The LSTM model consists of LSTM layers followed by one or more fully connected layers. The GRU model follows a similar architecture, but utilizes Gated Recurrent Units instead of LSTM units.



## Results

After training and evaluating the models,we got on mean absolute error (MAE) of 0.012

## Contributing

Contributions to the stock tracker project are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request. Please follow the existing code style and guidelines.



