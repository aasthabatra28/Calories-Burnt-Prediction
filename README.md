# 🔥 Calories Burnt Prediction

> Predict calories burned during workouts using XGBoost ML model

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-Regressor-orange.svg)](https://xgboost.ai)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF.svg)](https://kaggle.com)

## 🎯 What It Does

Predicts how many calories you'll burn based on:
- 👤 Gender, Age, Height, Weight
- ⏱️ Exercise Duration
- ❤️ Heart Rate & Body Temperature

## 🚀 Quick Start
```bash
pip install numpy pandas matplotlib seaborn xgboost scikit-learn kagglehub
```

## 📊 Workflow
```
Download Dataset → Merge Files → Clean Data → 
Visualize Patterns → Train XGBoost → Predict Calories
```

### Key Steps:
1. **Data Collection** - Downloaded from Kaggle using KaggleHub
2. **Data Merge** - Combined `exercise.csv` + `calories.csv`
3. **EDA** - Distribution plots, correlation heatmap
4. **Preprocessing** - Gender encoding (male→0, female→1)
5. **Model** - XGBoost Regressor (80/20 train-test split)
6. **Evaluation** - Mean Absolute Error (MAE)

## 🛠️ Tech Stack

`Python` `Pandas` `NumPy` `XGBoost` `Scikit-learn` `Matplotlib` `Seaborn`

## 📈 Model Performance

**Metric:** Mean Absolute Error  
*(Lower = Better predictions)*

## 💡 Usage
```python
model = XGBRegressor()
model.fit(X_train, y_train)
predictions = model.predict(X_test)
```

## 🎨 Visualizations

- Gender distribution count plot
- Age, Height, Weight distributions
- Feature correlation heatmap

---
