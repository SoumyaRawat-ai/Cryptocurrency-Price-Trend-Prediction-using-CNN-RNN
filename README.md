# 🧠 Crypto Price Prediction using CNN

This project implements a **Convolutional Neural Network (CNN)** model to predict cryptocurrency prices based on historical data. The goal is to leverage deep learning techniques to forecast price trends for assets like Bitcoin, Ethereum, and others.

## 📌 Features

- Historical crypto price data processing
- CNN model for trend prediction
- Data visualization (price movements, prediction accuracy)
- Model evaluation using metrics like MSE, RMSE
- Easy to modify for any coin or timeframe

## 📁 Project Structure
```
├── data/ # Raw and processed price data
├── models/ # CNN model definition
├── notebooks/ # Jupyter notebooks for EDA and training
├── utils/ # Helper functions (scaling, plotting, etc.)
├── main.py # Main training and prediction script
├── requirements.txt # List of dependencies
└── README.md # Project documentation
```

1. **Clone the repository**
```
git clone https://github.com/yourusername/crypto-cnn-predictor.git
cd crypto-cnn-predictor

```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the training script
```
python main.py
```

🧪 Requirements

Python 3.7+
NumPy
Pandas
TensorFlow / PyTorch
Matplotlib / Seaborn
Scikit-learn

)

📊 Results
The model shows promising performance in detecting short-term trends in cryptocurrency price data. Predictions closely follow actual price curves with a low mean squared error on test sets.


📈 Sample Visualization



📌 TODO
Add LSTM / hybrid CNN-LSTM model
Integrate real-time data fetching
Deploy with a web dashboard (e.g., Streamlit)


🤝 Contributing
Pull requests and suggestions are welcome! Please open an issue to discuss any major changes.

