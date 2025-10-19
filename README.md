# 📈 Stock Price Prediction using LSTM

This project predicts stock prices using a **Long Short-Term Memory (LSTM)** neural network built with **TensorFlow and Keras**.  
It performs **time series forecasting** on historical stock data, visualizes stock trends, and compares predicted vs actual closing prices.

---

## 🧠 Overview

Stock market prices are sequential and depend on past behavior — making **Recurrent Neural Networks (RNN)** ideal for modeling them.  
In this project, we use **LSTM**, a type of RNN that overcomes the *vanishing gradient problem* and captures long-term dependencies in data.


---

## 🗂️ Dataset

- Dataset: [`Link`](https://www.kaggle.com/dgawlik/nyse)  
- Contains 5 years of daily stock data for multiple companies.

## How to Run
1️⃣ Clone this repository
git clone https://github.com/keshavkumar-03/stock-price-prediction-lstm.git
cd stock-price-prediction-lstm

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the notebook/script

4️⃣ View Results
Prediction and trend plots generated automatically

💡 Future Improvements

-Add multi-feature training (e.g., open, high, low, volume)
-Implement Bidirectional LSTMs or GRUs
-Integrate real-time stock data using APIs (Yahoo Finance / Alpha Vantage)
-Deploy as a Streamlit or Flask web app

