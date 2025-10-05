# 👋 Hi, I'm John Wallace

Quantitative Strategy | Computer Science & Business | Trinity College Dublin (2025)

---

## 🧠 About This Site

Welcome to my machine learning and quantitative finance portfolio.  
Each project listed below includes code, results, and documentation.

---
## 📊 Projects

### 📌 [Forecasting Asset Class Performance with ML](https://github.com/JayWallace02/ml-asset-forecasting)
Forecasts monthly return and volatility for Bonds, Equities, and Gold using LSTM and Temporal Fusion Transformer (TFT).  
- ✅ Quantile predictions (5%, 50%, 95%)
- ✅ Rolling evaluation with interval scoring
- ✅ Dynamic portfolio allocation using MVO
- 📄 [View Thesis PDF](https://github.com/JayWallace02/ml-asset-forecasting/blob/main/FYP_Project_2025.pdf)

### 📌 S&P 500 Intraday Trading Strategy

A **machine learning–driven intraday trading system** that identifies statistically significant directional behavior in the **S&P 500** using 5-minute data.  
The strategy activates during **SMA crossover events**, refined through:

- 📈 **Temporal Fusion Transformer (TFT):** Quantile-based return forecasting  
- 🧠 **XGBoost Classifier:** Breakout validation and false-signal filtering  
- 🧮 **Regime Filtering:** Trades only in high-confidence market conditions  

#### 📊 Performance (Unseen Test Set)
| Metric | Value |
|:--|:--|
| **Sharpe Ratio** | **1.71** |
| **Annualized Return** | **64.48%** |
| **Max Drawdown** | **–18.2%** |
| **Total Trades** | **1,522** |

📄 [**View Strategy Report (PDF)**](./Sp500_Intra_day_breakout_Stratergy_Report.pdf)


---


## ⚙️ Tools Used

- Python, PyTorch, PyTorch Lightning
- PyTorch Forecasting, Optuna
- Pandas, NumPy, Scikit-learn
- Jupyter, Matplotlib

---


---

*© 2025 John Wallace — All content for academic demonstration only.*
