# Microsoft-Azure-AI-Project

# 🚦 Road Traffic Accident Severity Predictor (UK)

This machine learning project predicts the **severity of road traffic accidents** using historical UK accident data. Built using **Pandas, Scikit-learn, LightGBM, and Streamlit**, this model helps anticipate the risk level of a potential accident based on input features like time of day, road conditions, weather, and location metadata.

## 🔍 Features

- End-to-end ML pipeline: Data Cleaning → Feature Engineering → Model Training → Evaluation
- Multiple classifiers: Logistic Regression, Random Forest, XGBoost, LightGBM
- Visualizations: Seaborn & Matplotlib
- Handles class imbalance and categorical encoding

## 📊 Dataset

- Source: [Kaggle – UK Road Traffic Accident Dataset](https://www.kaggle.com/datasets/salmaneunus/road-traffic-accident-dataset)
- License: Public use

## 📈 Model Results

| Model             | Accuracy | Best Class |
|------------------|----------|------------|
| LogisticRegression | 36.8%   | Class 3    |
| RandomForest       | 49.6%   | Class 3    |
| LightGBM           | 53.9%   | Class 3    |
| **XGBoost**        | **85.4%** | **Class 3** (Imbalanced) |

