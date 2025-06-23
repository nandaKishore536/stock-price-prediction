
# 📈 Stock Price Prediction Using Python and Machine Learning

This project predicts the next day's closing stock price using historical stock price data and a simple Machine Learning model built with Python.

It demonstrates fetching real-time data, preparing it for analysis, building a prediction model, and visualizing the results.

---

## 🚀 Features

- Fetches real-time stock price data using `yfinance`
- Prepares data for next-day price prediction
- Trains a Linear Regression Machine Learning model
- Predicts next-day stock price based on current price
- Visualizes actual vs predicted prices using graphs

---

## 🛠️ Technologies & Libraries Used

- Python  
- yfinance → Fetch stock price data  
- pandas → Data handling  
- numpy → Numerical operations  
- matplotlib → Data visualization  
- scikit-learn → Machine Learning model (Linear Regression)  

---

## 📊 How it Works

1. Download stock price data for a company (Example: Tata Motors)
2. Prepare the dataset by shifting the closing price to predict the next day's price
3. Split the data into training and testing sets
4. Train a Linear Regression model to learn from the training data
5. Test the model and predict stock prices
6. Visualize the prediction results with a graph comparing actual vs predicted prices

---

## 📂 Project Files

- `stock_price_prediction.ipynb` → Google Colab notebook with all project code  
- `README.md` → Project description file  
- `requirements.txt` (Optional) → List of required Python libraries  

---

## 🖥️ How to Run

### Using Google Colab

- Open [Google Colab](https://colab.research.google.com/)  
- Upload the `stock_price_prediction.ipynb` notebook  
- Run all cells step by step  
- Visualize the predictions  

### Using Local System (VS Code, Terminal)

1. Install required libraries:
```bash
pip install yfinance pandas numpy matplotlib scikit-learn
```

2. Run your Python file:
```bash
python stock_price_prediction.py
```

---

## 📌 Example Output

- Table displaying downloaded stock price data  
- Predicted vs Actual stock price comparison  
- Graph showing:
  - Blue Dots → Actual Prices  
  - Red Dots → Predicted Prices  

---

## 🎯 Project Purpose

This project helps beginners understand:

- Fetching real-world financial data  
- Basics of data handling with pandas  
- Introduction to Machine Learning using Linear Regression  
- Visualizing results with matplotlib  

**Note:** This project is for educational purposes and not intended for real-world financial trading decisions.

---

## 🙌 Acknowledgements

- Data fetched using [Yahoo Finance API](https://finance.yahoo.com/).  
- Inspired by beginner-friendly Machine Learning tutorials.
