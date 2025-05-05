# Cryptocurrency Price Forecasting

This project focuses on forecasting cryptocurrency prices using deep learning techniques. The main goal is to predict the `close` price of cryptocurrencies based on historical data.

## Features
- Utilizes LSTM (Long Short-Term Memory) neural networks for time series prediction.
- Includes data preprocessing, normalization, and visualization.
- Provides performance metrics such as Mean Squared Error (MSE) and R² score.
- Generates visualizations comparing actual vs. predicted values.

## Dataset
The dataset includes the following columns:
- `date`
- `high`
- `low`
- `open`
- `Volume XRP`
- `Volume USDT`
- `close`

The data is preprocessed to keep only relevant columns and normalized for better performance in deep learning models.

## Setup and Requirements
### Prerequisites
- Python 3.6 or higher
- Required libraries: 
  - `tensorflow`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `google.colab` (if running in Google Colab)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/NaomyChemungor/Cryptocurrency_Price_Forecasting.git
   cd Cryptocurrency_Price_Forecasting
