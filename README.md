# Diabetes Classification

**Machine Learning Classification + MLOps Project** | Predicting diabetes risk using patient health metrics with systematic experiment tracking.

## 📋 Project Overview
This project builds and compares multiple machine learning models to predict whether a patient has diabetes. A modular, reproducible pipeline with **MLflow** experiment tracking was implemented to systematically log, compare, and manage model performance.

## 🎯 Business / Real-World Impact
Early diabetes prediction enables proactive healthcare interventions. This project demonstrates both strong predictive modeling and MLOps best practices for reproducible, trackable machine learning workflows.

## 🗂️ Dataset
- **Source**: Diabetes dataset ([Kaggle](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data))
- **Target**: Binary classification (`Diabetes` vs `No Diabetes`)
- **Features**: Blood glucose, BMI, insulin, blood pressure, age, pregnancies, skin thickness, and other clinical indicators.

## 🔧 Key Techniques & Models
- **Data Preprocessing**: Cleaning, feature scaling, and train/test splitting
- **Exploratory Data Analysis**: Feature distributions and correlation analysis
- **Modeling** (Modular Architecture):
  - Random Forest
  - Extra Trees
  - Gradient Boosting
  - XGBoost
  - LightGBM
  - CatBoost
- **MLOps Practices**:
  - Full experiment tracking with **MLflow** (parameters, metrics, and models)
  - Modular Python scripts for each model
  - Reproducible training pipelines
  - Systematic model comparison and logging

## 📊 Results
- Strong performance using ensemble tree-based models (XGBoost, LightGBM, and CatBoost performed best)
- Comprehensive model comparison and performance logging via **MLflow**
- Key predictive features identified (e.g., glucose levels, BMI, age)

## 📁 Repository Structure

## 📄 Reports
- [Full Project Report (PDF)](Diabetes%20Classification/Reports/Diabetes%20Classification%20Report.pdf)
- [Presentation Slides (PDF)](Diabetes%20Classification/Reports/Diabetes%20Classification%20Slides.pdf)

## 🛠️ Technologies Used
**Python** • **pandas** • **scikit-learn** • **XGBoost** • **LightGBM** • **CatBoost** • **MLflow** • **Matplotlib** • **Seaborn**
