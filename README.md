# Gold Price Forecasting – SARIMA–LSTM–RF Hybrid Model

This repository contains the dataset and source code for the research paper titled:

**Forecasting Daily Global Gold Prices Using a SARIMA–LSTM–RF Hybrid Model**

## 📊 Description

This study proposes a hybrid model that integrates:
- SARIMA (for linear and seasonal trends)
- LSTM (for nonlinear patterns from residuals)
- Random Forest (to incorporate macroeconomic indicators)

## 📁 Files Included

- `gold_macro_data.xlsx`: Combined dataset of gold price and macroeconomic indicators
- `SARIMA - LSTM - RF 2.ipynb`: Jupyter Notebook implementing the hybrid forecasting model

## ⚙️ Requirements

To run the notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow keras shap
