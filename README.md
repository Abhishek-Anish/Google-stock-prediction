**Overview**
This project focuses on predicting stock prices using a deep learning model, specifically Long Short-Term Memory (LSTM) networks. The application integrates live stock data, performs technical analysis, and evaluates predictions using various metrics.

**Features**
Live Stock Data Retrieval: Utilizes the Alpha Vantage API to fetch live stock data for a given ticker symbol.

**Technical Indicators: Computes multiple financial indicators:**
Simple and Exponential Moving Averages (SMA & EMA)
Relative Strength Index (RSI)
Bollinger Bands
Moving Average Convergence Divergence (MACD)
Average True Range (ATR)
Volume Weighted Average Price (VWAP)
Deep Learning Model: Implements an LSTM-based neural network for predicting stock prices.

**Evaluation Metrics:**
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Mean Absolute Percentage Error (MAPE)
Symmetric Mean Absolute Percentage Error (SMAPE)
Explained Variance Score (EVS)
Median Absolute Error (MedAE)

**Visualizations:**
Comparison of actual vs. predicted prices using Matplotlib.
Interactive visualizations with Plotly.

**Technologies Used**
Languages: Python
Libraries:
Data Manipulation: pandas, numpy
Visualization: matplotlib, plotly
API Interaction: alpha_vantage
Machine Learning: tensorflow.keras, scikit-learn

**Usage**
Place the Alpha Vantage API key file in the specified path (update the code if needed).
Update the ticker_symbol variable in the script to the desired stock symbol.
Run the script to fetch data, compute indicators, train the LSTM model, and generate predictions.
