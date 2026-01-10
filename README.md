# Financial Engineering Projects

This repository contains selected academic projects completed during my M.Sc. in Financial Engineering at
Karlsruhe Institute of Technology (KIT) – Hector School.

The projects focus on practical applications of quantitative finance, statistical modeling, and machine learning,
with an emphasis on interpretability, robustness, and academic correctness rather than production deployment.

---

## 1. Kalman Filter for Vasicek Interest Rate Model

**File:** `01_Kalman_Vasicek_MLE_Implementation.ipynb`

- Implemented a state-space representation of the Vasicek short-rate model.
- Estimated latent short-rate dynamics from noisy yield observations using Kalman Filtering.
- Calibrated model parameters via Maximum Likelihood Estimation (MLE).
- Visualized filtered state estimates versus observed yields.

**Supporting material:**
- `01A_Kalman_Vasicek_Theory_Notes.ipynb` – theoretical background and analytical derivations.
- `01B_Kalman_Vasicek_MLE_Exam_Solved.ipynb` – structured, exam-oriented implementation of the same framework.

---

## 2. Machine Learning for Return Prediction

**File:** `02_ML_Return_Prediction.ipynb`

- Built a return prediction pipeline using multiple regression and machine learning models
  (Lasso, Elastic Net, XGBoost, Random Forest).
- Evaluated out-of-sample performance using risk-adjusted metrics (Sharpe, Sortino).
- Assessed statistical significance of predictive performance using Diebold–Mariano tests.
- Incorporated transaction costs to reduce backtesting bias.

**Supporting material:**
- `02A_ML_Exam_Exercises.ipynb` – course exercises and exam-style implementations related to return prediction.

---

## Tools & Skills

- **Programming:** Python (NumPy, Pandas, SciPy, Statsmodels)
- **Machine Learning:** scikit-learn, XGBoost
- **Quantitative Finance:** Vasicek model, Kalman Filtering, MLE, risk modeling
- **Visualization:** Matplotlib, Seaborn

---

## About

These projects were developed as part of the Financial Engineering curriculum at
Karlsruhe Institute of Technology (KIT).
They are intended to demonstrate applied understanding of quantitative models and
sound modeling practices in an academic setting.
