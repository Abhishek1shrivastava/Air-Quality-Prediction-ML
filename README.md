# 🌿 Air Quality Index (AQI) Prediction — ML Project

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat&logo=scikit-learn)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)](https://jupyter.org)
[![Internship](https://img.shields.io/badge/Internship-AICTE%20%7C%20Shell%20%7C%20Edunet-green?style=flat)](https://edunetfoundation.org)

> **Internship Project** — AICTE · Shell India Markets Pvt. Ltd. · Edunet Foundation (Skills4Future Program)  
> 📅 Duration: 24 February 2025 – 24 March 2025

---

## 📌 Project Overview

This project was developed during a **4-week virtual internship** focused on AI & Data Analytics (Green Skills). The goal was to build a machine learning model that **predicts Air Quality Index (AQI)** values using historical pollutant measurements — enabling short-term air quality forecasting.

AQI prediction helps governments, researchers, and citizens understand air pollution levels and take timely preventive measures.

---

## 📊 Dataset

The dataset (`AQI_Dataset.csv`) contains historical air quality measurements with the following features:

| Feature | Description |
|---|---|
| `PM2.5` | Fine particulate matter (μg/m³) |
| `PM10` | Coarse particulate matter (μg/m³) |
| `NO2` | Nitrogen Dioxide concentration |
| `SO2` | Sulfur Dioxide concentration |
| `CO` | Carbon Monoxide concentration |
| `O3` | Ozone concentration |
| `Temperature` | Ambient temperature |
| `Humidity` | Relative humidity (%) |
| `AQI` | **Target variable** — Air Quality Index |

---

## 🔬 Methodology

```
Data Loading → EDA → Preprocessing → Feature Engineering → Model Training → Evaluation
```

### Steps Performed:
1. **Exploratory Data Analysis** — histograms, boxplots, correlation heatmaps
2. **Data Cleaning** — missing value imputation, duplicate removal, outlier handling
3. **Feature Engineering** — extracted temporal features (hour, day, month, weekday)
4. **Model Training** — trained and compared multiple regression models
5. **Evaluation** — MAE, RMSE, R² with k-fold cross-validation
6. **Model Selection** — chose best performer based on metrics

---

## 🤖 Models Compared

| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 12.5 | 18.2 | 0.62 |
| Decision Tree | 9.8 | 14.6 | 0.74 |
| **Random Forest** ✅ | **7.3** | **10.8** | **0.86** |
| Gradient Boosting | 6.9 | 10.2 | 0.88 |

> ✅ **Random Forest Regressor** was selected as the final model for its balance of accuracy and interpretability.

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas`, `NumPy` — data manipulation
  - `matplotlib`, `seaborn` — visualization
  - `scikit-learn` — model training & evaluation
  - `joblib` — model persistence

---

## 📁 Repository Structure

```
EdunetFoundation_Internship/
│
├── Air_Quality_index_prediction.ipynb   # Main project notebook
├── week1Project.ipynb                   # Week 1 assignment notebook
├── AQI_Dataset.csv                      # Dataset
└── README.md
```

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Abhishek1shrivastava/EdunetFoundation_Internship.git
cd EdunetFoundation_Internship
```

### 2. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

### 3. Open the notebook
```bash
jupyter notebook Air_Quality_index_prediction.ipynb
```

Run all cells to reproduce the results!

---

## 📅 Week-by-Week Progress

| Week | Dates | Tasks |
|---|---|---|
| Week 1 | 24 Feb – 2 Mar | Onboarding, dataset exploration, initial EDA |
| Week 2 | 3 Mar – 9 Mar | Feature engineering, baseline linear regression |
| Week 3 | 10 Mar – 16 Mar | Tree-based models, cross-validation, hyperparameter tuning |
| Week 4 | 17 Mar – 24 Mar | Final model, documentation, GitHub submission |

---

## 🏅 Internship Details

| Detail | Info |
|---|---|
| **Program** | Skills4Future — Green Skills |
| **Organizations** | AICTE · Shell India Markets Pvt. Ltd. · Edunet Foundation |
| **Supervisor** | Nagesh Singh (Chairman, Edunet Foundation) |
| **Duration** | 24 Feb 2025 – 24 Mar 2025 |
| **Mode** | Virtual Internship |

---

## 💡 Key Learnings

- End-to-end ML pipeline for regression tasks
- Data preprocessing and feature engineering on real-world environmental data
- Model comparison and selection using cross-validation
- Applied ethical AI principles to green energy analytics
- Version control and reproducible notebook practices

---

## 👤 Author

**Abhishek Shrivastava**  
B.Tech — Artificial Intelligence & Data Science  
Samrat Ashok Technological Institute, Vidisha (M.P.)

[![GitHub](https://img.shields.io/badge/GitHub-Abhishek1shrivastava-black?style=flat&logo=github)](https://github.com/Abhishek1shrivastava)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek--shrivastava--ai-blue?style=flat&logo=linkedin)](https://linkedin.com/in/abhishek-shrivastava-ai)
