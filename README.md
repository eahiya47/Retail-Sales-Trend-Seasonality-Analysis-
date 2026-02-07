# 🛒 Retail Sales Trend & Seasonality Analysis

## 📌 Project Overview

This project focuses on analyzing **retail sales trends and seasonal patterns** using time series analysis techniques.
Synthetic daily sales data is generated and analyzed to understand **trend, seasonality, stationarity, and noise** in retail sales over time.

The project is implemented using **Python** in a **Jupyter Notebook** environment.

---

## 🎯 Objectives

* Analyze long-term **sales trends**
* Identify **weekly and yearly seasonality**
* Perform **rolling statistics analysis**
* Check **stationarity** using the Augmented Dickey-Fuller (ADF) test
* Apply **time series decomposition**
* Visualize **autocorrelation and partial autocorrelation**

---

## 🛠️ Technologies Used

* Python 3.x
* Jupyter Notebook

### Libraries

* pandas
* numpy
* matplotlib
* seaborn
* statsmodels

---

## 📂 Project Structure

```
Retail-Sales-Trend-Seasonality-Analysis/
│
├── Retail_Sales_Trend_Seasonality_Analysis.ipynb
├── Retail Sales Trend & Seasonality Analysis.pdf
├── README.md
```

---

## 📊 Dataset

* The dataset is **synthetically generated**
* Daily sales data from **Jan 2022 to Dec 2024**
* Includes:

  * Trend component
  * Weekly seasonality
  * Yearly seasonality
  * Random noise

---

## 🔍 Methodology

1. Data generation and preprocessing
2. Exploratory data analysis (EDA)
3. Rolling mean and rolling standard deviation
4. Sales analysis by day of the week
5. Seasonal decomposition (Additive model)
6. Autocorrelation (ACF) and Partial Autocorrelation (PACF)
7. Stationarity testing using ADF test
8. Differencing to achieve stationarity
9. Residual (noise) analysis

---

## 📈 Key Results

* Sales show a **clear upward trend**
* Strong **weekly seasonality** detected
* Original series is **non-stationary**
* Differenced series becomes **stationary**
* Residuals resemble random noise after decomposition

---

## ▶️ How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/Retail-Sales-Trend-Seasonality-Analysis.git
   ```
2. Navigate to the project folder

   ```bash
   cd Retail-Sales-Trend-Seasonality-Analysis
   ```
3. Install required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels
   ```
4. Open Jupyter Notebook

   ```bash
   jupyter notebook
   ```
5. Run `Retail_Sales_Trend_Seasonality_Analysis.ipynb`

---

## 🚀 Future Enhancements

* Use a **real-world retail dataset**
* Implement **ARIMA / SARIMA forecasting**
* Add **monthly and quarterly analysis**
* Deploy as a **Streamlit dashboard**

---

## 👤 Author

Mohamed Eahiya S
Engineering Student

---

## 📜 License

This project is for **educational and academic purposes**.

---
