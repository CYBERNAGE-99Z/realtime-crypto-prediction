# Crypto Market Prediction Pipeline with Live API Integration

A machine learning project that predicts **future cryptocurrency prices** using historical data and real-time API integration.  
Built with Python, Scikit-learn, and CoinGecko API.  

---

## 📌 Features
- Data preprocessing & feature engineering (lags, rolling averages, returns).
- Multiple regression models (Linear Regression, Random Forest, XGBoost, SVR).
- Model evaluation using **RMSE** and **R² score**.
- Cross-validation for robust performance.
- Real-time prediction pipeline with live API data.

---

## 📊 Results
| Model              | RMSE    | R² Score |
|---------------------|---------|----------|
| Linear Regression   | 0.00195 | 0.9680   |
| Random Forest       | 0.0023  | 0.9539   |
| XGBoost             | 0.0024  | 0.9533   |

✅ **Linear Regression performed best** with R² ≈ 0.97.  
✅ Cross-validation confirmed strong performance (Mean R² ≈ 0.986).  

Example Real-Time Prediction:

- Timestamp: 2025-09-16 19:54:24
- Last Observed Price: $0.2684
- Predicted Return: +26.82%
- Predicted Next Price: $0.3403

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost
- **Visualization**: Matplotlib
- **Deployment**: Joblib (for model saving), CoinGecko API

---

## 📂 Project Structure

```bash
crypto-predictor/
│── models/ # trained pipeline (.pkl files)
  │──doge_price_model.pkl
  │──trained_pipeline.pkl
│── Real-time_pred.ipynb
│── cryptocurrency.csv
│── model_training.ipynb
│── requirements.txt # dependencies
│── README.md # documentation
│── .gitignore # ignored files

```


## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/crypto-predictor.git
cd crypto-predictor
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Open  the jupyter notebook
```bash
jupyter notebook "model_training.ipynb.ipynb"
jupyter notebook Real-time_pred.ipynb.ipynb"
```


📬 Contact

👤 Made with ❤️ by Akshansh Roy
🔗 [Linkedin](https://www.linkedin.com/in/akshansh-r-a7946b2a5/)
