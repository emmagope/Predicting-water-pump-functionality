# 💧 Predicting Water Pump Functionality

This repository contains my submission for the DrivenData competition [“Pump It Up: Data Mining the Water Table”](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/). The goal is to predict the functionality status of water pumps in Tanzania based on various environmental and operational features.

## 🧠 Problem Statement

This is a classification task where the target variable is `status_group` with three classes:
- `functional`
- `non functional`
- `functional needs repair`

## 📊 Workflow

- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training (RandomForest, XGBoost, etc.)
- Class balancing (SMOTE)
- Evaluation with F1-score
- Submission to DrivenData

## 🧰 Tools & Technologies

- Python (pandas, scikit-learn, matplotlib, seaborn, xgboost)
- Jupyter Notebooks
- Git/GitHub

## 🏆 Best score achieved

My best private leaderboard score was **0.8176**. 

## 📁 Repository structure

```bash
notebooks/        # Jupyter notebooks for EDA, modeling, submission
data/             # Data files (not included)
results/          # Visualizations and submission results
