
# ❤️ Heart Disease Prediction (Machine Learning)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)]()
[![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-yellow)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Predicting the likelihood of **heart disease** using classic clinical attributes with supervised machine learning.
This repository contains a reproducible Jupyter Notebook, ready-to-run environment, and exportable visuals for portfolios and reports.

---

## 📌 Highlights
- End‑to‑end workflow: **EDA → feature engineering → modeling → evaluation**
- Algorithms: **Logistic Regression, Decision Tree, Random Forest, SVM**
- Clear visualizations: **correlation heatmap, distributions, confusion matrix, model accuracy**
- Reproducible with `requirements.txt` and a single notebook: `Heart-disease-prediction-project.ipynb`

> Tip: Keep the `images/` folder updated by re‑running the notebook cells that save plots.

---

## 🧠 Problem Statement
Cardiovascular disease remains one of the top global health risks. Early risk prediction enables timely intervention.
We train and compare multiple classifiers to predict the **target** (presence of heart disease) from clinical features.

---

## 🗂️ Dataset (Typical Schema)
Common attributes in the UCI Cleveland Heart Disease–style dataset include:
- `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure), `chol` (serum cholesterol),  
  `fbs` (fasting blood sugar), `restecg` (resting ECG), `thalach` (max heart rate), `exang` (exercise angina),  
  `oldpeak` (ST depression), `slope`, `ca` (num major vessels), `thal`, and `target`.
- **Target**: 1 = disease present, 0 = no disease.

> If your columns differ, update this section to match your data.

---

## 📈 Key Visuals (exported from the notebook)
Place the generated images in `images/` (the notebook includes code to save them).

<p align="center">
  <img src="images/correlation_heatmap.png" alt="Correlation Heatmap" width="45%"/>
  <img src="images/age_distribution.png" alt="Age Distribution" width="45%"/>
</p>
<p align="center">
  <img src="images/confusion_matrix.png" alt="Confusion Matrix" width="45%"/>
  <img src="images/model_accuracy.png" alt="Model Accuracy Comparison" width="45%"/>
</p>

---

## 🔧 Methods
- **Preprocessing**: missing values check, type casting, scaling/encoding as needed
- **EDA**: distributions, correlations, class balance
- **Modeling**: Logistic Regression, Decision Tree, Random Forest, SVM
- **Validation**: train/test split, metrics (Accuracy, Precision, Recall, F1), confusion matrix

> You can extend this with cross‑validation and hyper‑parameter tuning (GridSearchCV/RandomizedSearchCV).

---

## ✅ Example Results (to update with your run)
- Best model: _Random Forest_ or _Logistic Regression_ (often strong baselines)  
- Report metrics (example placeholders; replace with your actual results):
  - Accuracy: `XX.X%`
  - Precision: `XX.X%`
  - Recall: `XX.X%`
  - F1‑score: `XX.X%`

> Replace placeholders after running the notebook and exporting your metrics.

---

## 🚀 Quickstart

```bash
# 1) Clone
git clone https://github.com/YOUR_USERNAME/heart-disease-prediction.git
cd heart-disease-prediction

# 2) (Optional) create a virtual environment
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

# 3) Install dependencies
pip install -r requirements.txt

# 4) Launch Jupyter
jupyter notebook
# Open: Heart-disease-prediction-project.ipynb
```

> After running the notebook cells that save figures, commit the new images:
```bash
git add images/*.png
git commit -m "Add exported visuals"
git push origin main
```

---

## 📦 Project Structure
```
heart-disease-prediction/
├─ Heart-disease-prediction-project.ipynb
├─ README.md
├─ requirements.txt
├─ LICENSE
├─ .gitignore
├─ data/
│  └─ README.md                 # place dataset or link here (keep raw data private if needed)
└─ images/
   ├─ correlation_heatmap.png
   ├─ age_distribution.png
   ├─ confusion_matrix.png
   └─ model_accuracy.png
```

---

