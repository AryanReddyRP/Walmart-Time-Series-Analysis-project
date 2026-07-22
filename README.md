# 📈 Walmart Weekly Sales Forecasting using SARIMA

A time series forecasting project that predicts **Walmart weekly sales** using the **Seasonal AutoRegressive Integrated Moving Average (SARIMA)** model. The project performs exploratory time series analysis, stationarity testing, seasonal decomposition, and forecasting to capture long-term trends and seasonal sales patterns.

---

## 📌 Project Overview

Accurate sales forecasting enables retailers to optimize inventory, staffing, and business planning. This project analyzes Walmart's historical weekly sales data to identify trends, seasonality, and external influences before building a **SARIMA** model for future sales prediction.

---

## 🚀 Features

- Time Series Exploratory Data Analysis (EDA)
- Trend and Seasonality Analysis
- Seasonal Decomposition
- Stationarity Testing using Augmented Dickey-Fuller (ADF) Test
- Automatic model selection using Auto ARIMA
- Sales forecasting using SARIMA
- Forecast visualization for future weeks

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- pmdarima

---

## 📂 Dataset

- **Dataset:** Walmart Weekly Sales
- **Problem Type:** Time Series Forecasting
- **Target Variable:** Weekly Sales

The dataset contains historical weekly sales records along with additional features such as holidays, temperature, fuel prices, CPI, and unemployment.

---

## 🔄 Data Analysis

The project includes:

- Data cleaning and preprocessing
- Date conversion and indexing
- Trend analysis
- Seasonal pattern identification
- Correlation analysis of external variables
- Store-wise sales comparison
- Time series visualization

---

## 🧠 Forecasting Model

The forecasting pipeline consists of:

- Seasonal Decomposition
- Augmented Dickey-Fuller (ADF) Test
- Auto ARIMA for parameter selection
- Seasonal ARIMA (SARIMA) model training
- Future sales forecasting

---

## 🔄 Workflow

1. Load and preprocess the Walmart sales dataset.
2. Perform exploratory data analysis.
3. Analyze trends and seasonal patterns.
4. Test stationarity using the ADF test.
5. Select model parameters using Auto ARIMA.
6. Train the SARIMA model.
7. Forecast future weekly sales.
8. Visualize actual and predicted sales.

---

## 📊 Model Evaluation

The project evaluates forecasting performance through:

- Time series visualization
- Actual vs Forecast comparison
- Trend and seasonality analysis
- Forecast for future weeks

---

## 📁 Repository Structure

```text
├── Walmart_TSA.ipynb
├── README.md
└── walmart_sales.csv
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Place the Walmart dataset in the project directory.
4. Open the Jupyter Notebook.
5. Execute all cells sequentially.
6. Generate forecasts and visualize future weekly sales.

---

## 📈 Future Improvements

- Compare SARIMA with Prophet, LSTM, and XGBoost forecasting models.
- Incorporate additional external variables for multivariate forecasting.
- Perform hyperparameter tuning for improved accuracy.
- Deploy the forecasting model as an interactive dashboard using Streamlit.

---

## 👨‍💻 Author

**Aryan Reddy**

If you found this project useful, consider giving the repository a ⭐.
