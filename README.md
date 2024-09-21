# NIFTY50-Prediction
This project focuses on predicting the next-day prices for the NIFTY50 stock market index, including open, high, low, and close prices. It leverages historical stock data, India vix data and machine learning techniques to forecast future prices.

# Disclaimer
Do not use this project for investment or trading purposes.
The predictions provided by this model are based solely on historical data and statistical methods. The stock market is influenced by a wide range of factors, such as:
- Foreign Institutional Investors (FII)
- Domestic Institutional Investors (DII)
- Current affairs
- Economic conditions
- Global market trends
- Geopolitical events

# Project Overview
NIFTY50 is one of the major stock market indices in India. Predicting its future price is crucial for making informed trading decisions. This project uses a machine learning-based approach to predict:
- Open Price
- High Price
- Low Price
- Close Price

The predictions are made using historical data and statistical methods, ensuring reasonable accuracy by providing error margins along with predicted values.

# Usage
1. Open the notebook `NIFTY50 Prediction.ipynb`.
2. Run the cells sequentially. The notebook will:
   - Load historical data.
   - Preprocess the data.
   - Train machine learning models.
   - Provide the next day's predicted prices with error margins.

3. Example output:
   ```
   Prediction for NIFTY50 (21-09-2024):
   Predicted Open Price: 25428.13 (25413.03 to 25443.23)
   Predicted High Price: 25546.31 (25528.85 to 25563.77)
   Predicted Low Price: 25297.27 (25277.88 to 25316.66)
   Predicted Close Price: 25433.12 (25410.99 to 25455.25)
   ```

# Model Overview
The project uses machine learning models, particularly regression-based techniques, to predict future prices. Four separate Linear Regression models are used to predict the following:
- Open Price
- High Price
- Low Price
- Close Price

Each model is trained individually on historical stock prices and India Vix, with relevant features such as trading volume, technical indicators, and past price movements. The models are evaluated based on metrics like Mean Absolute Error (MAE) to ensure accuracy, and confidence intervals are provided alongside the predictions to account for potential error margins.

# Results
The model provides accurate predictions within a small error range for the NIFTY50 index. The predicted prices include a confidence interval based on the model’s performance during testing.

# Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open a pull request.

# License
This project is licensed under the MIT License.

