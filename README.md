# 📊 TATA Stock Price Prediction (LSTM Model)

This project predicts TATA stock prices using an LSTM neural network. The goal is to train the model on past stock data and predict how the prices move in the future 📈

---

## 🧾 What I Used

- **Dataset:** TATA stock prices (Open column) from [this CSV](https://raw.githubusercontent.com/mwitiderrick/stockprice/master/NSE-TATAGLOBAL.csv)  
- **Libraries:** NumPy, Pandas, Matplotlib, scikit-learn, Keras  
- **Model:** 4-layer stacked LSTM with dropout and a dense output layer  
- **Loss function:** Mean Squared Error  
- **Optimizer:** Adam

---

## ⚙️ How It Works

- Trained on past 60-day windows of stock prices  
- Scaled values between 0 and 1 for better learning  
- Model learns patterns from historical data  
- Then it predicts next-day stock prices on test data  
- Results are plotted to compare actual vs predicted prices

---

## 📉 Output

The plot shows:
- **Black line** → Actual prices  
- **Green line** → Predicted prices

Looks pretty close! 🎯

---

## 💡 What’s Next?

This was a basic version using just the "Open" price. We can:
- Add more features (like High, Low, Volume)
- Tune the model
- Even deploy it as a web app with Streamlit or Flask 🚀

---

## 🛠 Run It Yourself

```bash
pip install numpy pandas matplotlib scikit-learn keras
