# airbnb-review-score-prediction

## 📌 Project Overview
This project uses machine learning to predict review scores for Airbnb listings in New York City. The goal is to help hosts understand what features drive positive reviews.

## 🎯 Objectives
- Build a regression model to predict review scores.
- Use unstrucutred text data to train model
- Improve model performance through feature engineering and tuning.

## 🔍 Methodology
- Performed EDA and data cleaning using Pandas and Seaborn.
- Engineered new features from descriptions and about sections
- Trained and evaluated models including linear regression

## 📊 Results & Findings
- Achieved MAE: 0.29, RMSE: 0.50
- Visualized prediction accuracy and residuals.

## 📈 Visualizations
Included in notebook:
- Correlation heatmaps
- Prediction vs. Actual plots
- Feature importance graphs

## 🧠 Future Work
- Experiment with neural networks and ensemble models
- Incorporate text data from reviews using NLP
- Automate retraining pipeline for new listings

## 👩🏽‍💻 My Contributions
- Project planning and problem definition  
- Data wrangling and feature engineering  
- Model training, evaluation, and documentation

## 📁 Sample Data
A small sample of the original dataset is included in the `data/` folder for testing purposes.

## 📝 How to Run This Project

1. Clone the repo:
```bash
git clone https://github.com/msreenam/airbnb-review-score-prediction
cd airbnb-review-score-prediction
```
2. Install requirements:
```bash
pip install -r requirements.txt
```
3. Run the notebook
```bash
jupyter notebook airbnb_model.ipynb
```
