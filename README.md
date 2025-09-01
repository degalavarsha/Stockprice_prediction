# Stock Price Prediction with LSTM

This project demonstrates stock price prediction using a **Long Short-Term Memory (LSTM)** recurrent neural network in Python. The model is trained on historical stock data of **Apple Inc. (AAPL)** and makes predictions on future stock prices.

---

## Features

* Downloads historical stock data with **yfinance**
* Preprocesses data with **MinMaxScaler**
* Builds and trains an **LSTM model** for stock prediction
* Evaluates model performance using **RMSE**
* Visualizes actual vs. predicted prices
* Demonstrates predicting the next day's closing price

---

## Steps in the Notebook

1. **Import Libraries** – NumPy, Pandas, Matplotlib, TensorFlow/Keras, yfinance
2. **Data Acquisition** – Fetch stock data (AAPL: 2020–2024)
3. **Data Exploration** – Visualize closing prices
4. **Data Preparation** – Scaling, train-test split, sequence creation
5. **Model Building** – LSTM layers + Dense layers
6. **Model Training** – Adam optimizer + MSE loss
7. **Model Evaluation** – Predictions vs. actual data
8. **Visualization** – Compare actual vs. predicted stock prices
9. **Future Prediction** – Predict stock price for a given date

---

## How to Run

1. Open the notebook in **Google Colab**
2. Run each cell step by step
3. Make sure to install missing packages (e.g., yfinance):

   ```python
   !pip install yfinance
   ```
4. Execute all cells to train and test the LSTM model

---

## Results

* The model provides predictions close to actual stock prices
* Visual comparison charts show trends between actual and predicted values
* Can be extended to other stock symbols by changing the ticker in `yfinance.download()`

---



