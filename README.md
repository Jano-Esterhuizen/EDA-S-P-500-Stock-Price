# 📈 S&P 500 Stock Price Exploration and Web App

This repository contains an **Exploratory Data Analysis (EDA)** notebook and a **Streamlit web application** to analyze and visualize **S&P 500** stock data. The project consists of:

- 📝 **EDA Notebook (`EDA_SP500_Stock_Price.ipynb`)**: Analyzes stock price data and explores insights for web app development.
- 🌐 **Web Application (`sp500-app.py`)**: A **Streamlit** dashboard to fetch, filter, and visualize **S&P 500** stock closing prices.

---

## 📊 **Exploratory Data Analysis (EDA)**
The **`EDA_SP500_Stock_Price.ipynb`** notebook performs:
- 📌 **Data retrieval**: Extracts **S&P 500 stock price data**.
- 📊 **Data visualization**: Generates stock performance charts.
- 🔎 **Preliminary insights**: Helps define the key features for the web app.

---

## 🖥️ **S&P 500 Stock Price Web App**
The **Streamlit application (`sp500-app.py`)** allows users to:
1. **Fetch S&P 500 stock data** 📲 from [Wikipedia](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies).
2. **Filter stocks by sector** 🔍 using a sidebar.
3. **Download stock data as a CSV** 💽.
4. **Visualize closing prices** 📊 using `matplotlib`.

### 🚀 **Run the Web App**
Ensure you have **Python** and the required dependencies installed.

1️⃣ **Install dependencies**:
```bash
pip install streamlit pandas matplotlib seaborn numpy yfinance
```

2️⃣ **Run the app**:
```bash
streamlit run sp500-app.py
```

---

## 📂 **Project Structure**
```
👤 S&P-500-Stock-App
├── 📝 EDA_SP500_Stock_Price.ipynb  # Exploratory Data Analysis Notebook
├── 📝 sp500-app.py                 # Streamlit Web App
├── 📝 README.md                     # Project Documentation
```

---

## ⚙️ **Features**
✅ **Fetch real-time stock data** from Yahoo Finance 📊  
✅ **Filter stocks by industry sector** 🎯  
✅ **Download stock data as CSV** 📂  
✅ **Visualize closing price trends** 📉  

---

## 🛠️ **Technologies Used**
- **Python** 🐍
- **Streamlit** 🌐
- **pandas** 📊
- **matplotlib & seaborn** 🎨
- **yfinance** 📈 (Yahoo Finance API)

---

## 🎯 **Future Enhancements**
🔹 Add interactive stock comparisons  
🔹 Implement technical indicators (moving averages)  
🔹 Integrate machine learning for trend predictions 
