# 🚀 Crypto Price Predictor (Dogecoin Example)

A machine learning project that predicts **future cryptocurrency prices** using historical data and real-time API integration.  
Built with Python, Scikit-learn, and CoinGecko API.  

---

## 📌 Features
- Data preprocessing & feature engineering (lags, rolling averages, returns).
- Multiple regression models (Linear Regression, Random Forest, XGBoost, SVR).
- Model evaluation using **RMSE** and **R² score**.
- Cross-validation for robust performance.
- Real-time prediction pipeline with live API data.
- (Optional) Streamlit dashboard for visualization.

---

## 📊 Results
| Model              | RMSE    | R² Score |
|---------------------|---------|----------|
| Linear Regression   | 0.00195 | 0.9680   |
| Random Forest       | 0.0023  | 0.9539   |
| XGBoost             | 0.0024  | 0.9533   |
| SVR                 | 0.0203  | -2.4724  |

✅ **Linear Regression performed best** with R² ≈ 0.97.  
✅ Cross-validation confirmed strong performance (Mean R² ≈ 0.986).  

Example Real-Time Prediction:

```
- Timestamp: 2025-09-16 19:54:24
- Last Observed Price: $0.2684
- Predicted Return: +26.82%
- Predicted Next Price: $0.3403
```
---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, XGBoost)
- **Visualization**: Matplotlib, Streamlit
- **Deployment**: Joblib (for model saving), CoinGecko API

---

## 📂 Project Structure

```bash
crypto-predictor/
│── data/ # optional, small sample CSVs
│── models/ # trained pipeline (.pkl files)
│── notebooks/ # Jupyter notebooks (exploration/training)
│── src/ # source code
│ │── features.py # feature engineering functions
│ │── train.py # training script
│ │── predict.py # real-time prediction script
│ │── fetch_data.py # API fetching functions
│── app.py # Streamlit dashboard (optional)
│── requirements.txt # dependencies
│── README.md # documentation
│── .gitignore # ignored files

```


## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/crypto-predictor.git
cd crypto-predictor
```
