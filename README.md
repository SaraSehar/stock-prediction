# 📈 Stock Price Prediction

A machine learning project that predicts stock prices using historical data, built with Python in a Jupyter Notebook.

## ✨ Features
- Fetches historical stock data using `yfinance`
- Performs exploratory data analysis and visualizations
- Trains a machine learning model (Random Forest Regressor) to predict prices
- Evaluates performance using metrics like R², MAE, RMSE
- Visualizes actual vs. predicted prices and feature importance

## 📊 Dataset
Historical stock data (e.g., Apple Inc.) is retrieved via `yfinance`. The dataset includes Open, High, Low, Close, Volume, and derived technical indicators.

## 🛠️ Installation
```bash
# Clone the repository
git clone https://github.com/SaraSehar/stock-prediction.git
cd stock-prediction

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


# Install dependencies
pip install -r requirements.txt
Dependencies: pandas, numpy, matplotlib, seaborn, scikit-learn, yfinance
