# stock_prediction
# Intro
This is a  humble exercise in conquering the all-time contradiction of using historical data to predict future stock prices. Built with Streamlit, it offers an interactive platform for users to input stock symbols, visualize historical data, and view future price predictions.

# Features
- Interactive Interface: A web app developed using Streamlit for an engaging user experience.
- Real-Time Stock Data: Fetches the latest stock data from Yahoo Finance.
- Historical Trend Visualization: Displays historical stock price movements.
- Predictive Analysis: Uses LSTM (Long Short-Term Memory) neural networks to forecast stock prices.
- Data Visualization: Employs Matplotlib for graphical representation of stock trends and predictions.

# Installation
Clone the project and install dependencies:
```
git clone https://github.com/yourusername/stock_prediction.git
cd stock_prediction
pip install -r requirements.txt
```

# Usage
To run the app locally:
```
streamlit run stock_prediction.py
```

Visit http://localhost:8501 in your browser, enter a stock symbol, and explore the predictions.

# Technologies Used
- Python
- Streamlit
- TensorFlow/Keras - For LSTM models
- yfinance - To fetch stock data
- Pandas and NumPy - For data handling
- Matplotlib - For plotting data

# Contributing
Feel free to fork the repo and submit pull requests with your enhancements.

# Acknowledgments
- Thanks to Yahoo Finance for stock market data.
- Gratitude to TensorFlow and Keras for machine learning capabilities.
- Acknowledging Streamlit for the web application framework.
