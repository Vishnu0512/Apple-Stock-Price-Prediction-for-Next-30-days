# 📈 Stock Market Price Prediction

A time series forecasting project that predicts future stock prices using ARIMA and SARIMA models built with Python.

---

## 📌 Project Description

Predicting stock prices is a major challenge for investors who want to make smarter financial decisions. This project uses historical daily stock market data to build forecasting models that can predict future prices. The dataset contains daily records including **Open, High, Low, Close, Adjusted Close, and Volume** values starting from 2012. Python was used for data cleaning, visualization, and building time series models. The final models were saved as reusable files, allowing future predictions without retraining.

---

## 📂 Dataset

| Column       | Description                          |
|--------------|--------------------------------------|
| Date         | Trading date                         |
| Open         | Opening price of the day             |
| High         | Highest price of the day             |
| Low          | Lowest price of the day              |
| Close        | Closing price of the day             |
| Adj Close    | Adjusted closing price               |
| Volume       | Number of shares traded              |

---

## 🛠️ Tools & Libraries

| Tool / Library   | Purpose                              |
|------------------|--------------------------------------|
| Python           | Core programming language            |
| Pandas           | Data loading and cleaning            |
| Matplotlib       | Data visualization and charts        |
| Statsmodels      | ARIMA & SARIMA model building        |
| Pickle           | Saving and loading trained models    |
| Jupyter Notebook | Interactive development environment  |

---

## 🔍 Project Workflow

1. **Data Loading** — Imported stock market CSV data using pandas
2. **Data Cleaning** — Handled missing values and formatted date columns
3. **Exploratory Analysis** — Plotted price trends and volume over time
4. **Model Building** — Built ARIMA and SARIMA models for forecasting
5. **Model Evaluation** — Checked model accuracy on historical data
6. **Model Saving** — Exported trained models as `.pkl` files for reuse

---

## 📊 Models Used

- **ARIMA** *(AutoRegressive Integrated Moving Average)* — Captures trends and patterns in stock price data
- **SARIMA** *(Seasonal ARIMA)* — Extends ARIMA by also capturing seasonal patterns in the data

---

## 🎯 Outcome

The models successfully learned patterns from historical stock price data and can forecast future prices. The trained models are saved as reusable `.pkl` files, making it easy to load and predict at any time without retraining from scratch.

---

## 💡 Skills Gained

- Cleaning and preparing real-world time series data
- Visualizing stock trends and identifying patterns
- Building and tuning ARIMA and SARIMA forecasting models
- Saving and reusing machine learning models using Pickle
- Applying Python to solve real-world financial problems

---

## 📁 Project Files

```
├── Stock_Market.csv          # Raw stock market dataset
├── S_Market.ipynb            # Jupyter notebook with full analysis
├── arima_model.pkl           # Saved ARIMA model
├── sarima_model.pkl          # Saved SARIMA model
├── feature_cols.pkl          # Saved feature columns
├── last_row.pkl              # Last data row for prediction input
└── Business_Objective.docx   # Project business objective document
```

---

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/stock-market-prediction.git
   ```
2. Install required libraries
   ```bash
   pip install pandas matplotlib statsmodels jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook S_Market.ipynb
   ```

---

## 📬 Contact

Feel free to reach out for any questions or collaboration opportunities!
