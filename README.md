# 🍅 Vegetable Shelf-Life Regression using Random Forest

**Student:** Sneha S Kulkarni | **USN:** 4NI23IS211

---

## Project Overview
Predict the remaining shelf life (in days) of stored tomatoes using a **Random Forest Regressor** trained on four features:
- Brix Value (sugar content)
- Firmness (physical hardness)
- Storage Temperature (°C)
- Relative Humidity (%)

---

## Files in this Project

| File | Description |
|------|-------------|
| `Vegetable_ShelfLife_Regression.ipynb` | Main Jupyter Notebook (source) |
| `Vegetable_ShelfLife_Regression_Executed.ipynb` | Executed notebook with all outputs |
| `distribution_plots.png` | Feature distribution histograms |
| `correlation_heatmap.png` | Correlation matrix heatmap |
| `actual_vs_predicted.png` | Actual vs Predicted scatter plot |
| `feature_importance.png` | Feature importance bar chart |
| `residual_diagnostics.png` | Residual plot + histogram |

---

## How to Run

1. Install dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

2. Launch Jupyter:
```bash
jupyter notebook Vegetable_ShelfLife_Regression.ipynb
```

3. Run all cells (Kernel → Restart & Run All).

---

## Model Performance (Expected)

| Metric | Score |
|--------|-------|
| MAE    | ~0.50 days |
| RMSE   | ~0.70 days |
| R²     | ~0.98      |

---

## Algorithm
Random Forest Regressor — an ensemble of 100 decision trees that averages predictions to reduce overfitting and improve accuracy.
