# Stock Price Prediction using LSTM

This project implements a stock price prediction model using **Long Short-Term Memory (LSTM)** networks. The model predicts stock prices based on historical data and evaluates performance using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score. Additionally, it calculates trend direction accuracy to measure how well the model predicts whether the stock price will rise or fall.

## 📌 Features
- Data preprocessing using **MinMaxScaler**
- Time series data splitting using **scikit-learn**
- Stock price prediction using **LSTM (Long Short-Term Memory)**
- Model evaluation using **MSE, RMSE, and R² Score**
- Trend direction accuracy calculation

## 📂 Project Structure
```
📁 stock_price_prediction_nvda
│── stock_price_prediction_nvda.ipynb   # Jupyter Notebook with full implementation
│── requirements.txt                    # Required dependencies
│── README.md                            # Project documentation
```

## 🛠️ Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/ns-0437/stock-price-prediction.git
cd stock-price-prediction
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

## 🚀 How to Run the Model
1. Open the **Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```
2. Run all the cells in `stock_price_prediction_nvda.ipynb`.
3. The model will be trained and evaluated automatically.

## 📊 Model Evaluation Metrics
- **Mean Squared Error (MSE):** Measures the average squared difference between predicted and actual values.
- **Root Mean Squared Error (RMSE):** Standard deviation of residuals, measuring typical prediction error.
- **R² Score:** Measures how well the model explains variance in stock prices.
- **Trend Direction Accuracy:** Measures how often the model correctly predicts the stock price movement (up/down).

## 📈 Results (Example Output)
```
Mean Squared Error (MSE): 22.03
Root Mean Squared Error (RMSE): 4.69
R² Score: 0.9923
Trend Direction Accuracy: 74.05%
```

## 🛠️ Possible Improvements
- Add **technical indicators** like RSI, MACD, Bollinger Bands.
- Try **GRU or Bi-LSTM** for better time series modeling.
- Fine-tune hyperparameters (LSTM units, learning rate, dropout rate).
- Train on **larger datasets** to improve generalization.

## 📜 License
This project is open-source and available under the **MIT License**.

---
📧 **Author:** Navin Kumar
🔗 **GitHub:** [ns-0437](https://github.com/ns-0437)
