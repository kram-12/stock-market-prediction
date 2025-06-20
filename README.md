# 📈 Stock Market Prediction using Machine Learning

This project explores the application of Machine Learning models to predict stock prices for six major companies—Agilent Technologies Inc. (A), American Airlines Group Inc. (AAL), Advance Auto Parts Inc. (AAP), Apple Inc. (AAPL), AbbVie Inc. (ABBV), and NVIDIA Corporation (NVDA).

We focus on predicting the **High** stock price using historical stock data and apply three ML models:  
- 🟦 Random Forest (RF)  
- 🟩 Support Vector Machine (SVM)  
- 🧠 Artificial Neural Networks (ANN)

> **Repository link:** https://github.com/kram-12/stock-market-prediction

---

## 📊 Dataset

Each CSV contains:
- **Features**: `Open`, `High`, `Low`, `Close`, `Volume`, `Dividends`, `Stock Splits`
- **Frequency**: Daily  
- **Preprocessing**: Handled missing values and feature scaling before model training.

---

## 🎯 Objective

Predict the `High` stock price using available features and compare the performance of RF, SVM, and ANN models.

---

## 🧪 Models & Evaluation

The following metrics were used to evaluate model performance:
- **MAE** – Mean Absolute Error  
- **MSE** – Mean Squared Error  
- **RMSE** – Root Mean Squared Error  
- **R² Score** – Coefficient of Determination

### ✅ Results Summary

| Model | MAE ↓ | MSE ↓ | RMSE ↓ | R² ↑ |
|-------|-------|--------|---------|------|
| Random Forest | Moderate | Moderate | Moderate | Moderate |
| SVM           | Higher  | Higher  | Higher  | Lower    |
| **ANN**       | **Lowest** | **Lowest** | **Lowest** | **Highest** |

📌 The **Artificial Neural Network** outperformed the other models, showcasing its strength in capturing complex, non-linear relationships in stock price behavior.

---

## 📷 Visualizations

You can find result plots directly in the repository for quick visual comparison.

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/kram-12/stock-market-prediction.git
   cd stock-market-prediction
   ```

2. **Install dependencies**
   Use Jupyter Notebook or a Python environment with the following packages:

   * `pandas`
   * `numpy`
   * `matplotlib`
   * `seaborn`
   * `scikit-learn`
   * `tensorflow` or `keras`

3. **Run the notebook**
   Launch `code.ipynb` to start exploring.

---

## 📌 Conclusion

This project demonstrates that machine learning, particularly **ANN**, is a powerful tool for financial forecasting. Accurate stock price predictions can enhance investment strategies and support data-driven decision-making in financial markets.

---

## 📬 Contact

Feel free to raise an issue or reach out if you’d like to collaborate or have questions.

> ⭐ Star this repository if you found it helpful!

---
