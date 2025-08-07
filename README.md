# Stock-Price-Prediction-using-LSTM
This project leverages machine learning and deep learning to predict stock price trends using historical and technical indicator data. It utilizes a Recurrent Neural Network (RNN) architecture with LSTM layers for time-series forecasting, effectively capturing sequential dependencies in stock movements.

The model is trained on real-world stock market data fetched dynamically via yfinance, and enhanced with key technical indicators such as RSI (Relative Strength Index), MACD, EMA (Exponential Moving Average), and volatility measures using the ta library. The dataset includes multiple features—Open, High, Low, Close, Volume, and derived indicators—to provide richer market context.

Preprocessing is handled using MinMaxScaler, with careful attention to avoiding data leakage by fitting only on the training set. The model’s performance is optimized using tuned hyperparameters and evaluated using metrics such as RMSE (Root Mean Square Error) and MAE (Mean Absolute Error). Visualizations help compare predicted and actual trends.

The application is made dynamic using ipywidgets to allow real-time user input of ticker symbols and date ranges directly within a Jupyter notebook environment, enabling flexible experimentation and model retraining.
