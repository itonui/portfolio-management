# Portfolio Management & Risk Analysis System

## 📌 Project Overview
This project is a **Portfolio Management System** that automates stock price updates, analyzes portfolio performance, optimizes asset allocation, and predicts stock prices using **Machine Learning (LSTM)**. It also includes an **email alert system** for price drops.

##  Features
- ✅ **Real-time Stock Price Updates** using Yahoo Finance API
- ✅ **Portfolio Performance Analysis** (Profit/Loss, Returns)
- ✅ **Stock Price Prediction** using LSTM Neural Networks
- ✅ **Portfolio Optimization** using Modern Portfolio Theory (MPT)
- ✅ **Automated Email Alerts** for stock price drops

---
## 🔧 Setup Instructions
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/portfolio-management.git
cd portfolio-management
```

### **2️⃣ Install Dependencies**
Ensure you have Python 3.7+ installed. Then, install the required packages:
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Main Script**
To start the system, run:
```bash
python portfolio_management.py
```

---
## 📊 Usage Guide
### **1️⃣ Update Stock Prices**
```python
update_prices()
```
Fetches real-time stock prices and updates the SQLite database.

### **2️⃣ Analyze Portfolio Performance**
```python
analyze_portfolio()
```
Calculates total investment, current value, returns, and risk metrics.

### **3️⃣ Predict Stock Prices using LSTM**
```python
train_lstm_model("AAPL")
```
Trains an LSTM model on historical stock data and forecasts future prices.

### **4️⃣ Optimize Portfolio using Modern Portfolio Theory**
```python
optimize_portfolio()
```
Computes the best asset allocation to maximize returns while minimizing risk.

### **5️⃣ Monitor and Send Alerts**
```python
monitor_stocks()
```
Checks stock prices and sends email alerts if prices drop below thresholds.

---
## 🛠️ Technologies Used
- **Python** (pandas, numpy, matplotlib, sqlite3)
- **Machine Learning** (TensorFlow, scikit-learn)
- **Finance APIs** (yfinance)
- **Database** (SQLite)
- **Email Alerts** (smtplib)

---
## 🤝 Contribution
Feel free to fork this project and submit pull requests!



