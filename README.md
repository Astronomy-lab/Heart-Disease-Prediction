# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Overview

This project predicts the likelihood of heart disease using patient medical data and a Random Forest Classifier. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, feature importance analysis, and model saving for future predictions.

## 🎯 Objective

Develop a machine learning model to predict whether a patient has heart disease based on clinical and medical attributes.

## 📂 Dataset

* **Dataset:** UCI Heart Disease Dataset
* **Target Variable:** `num` (converted to binary `target`)

  * `0` → No Heart Disease
  * `1` → Heart Disease

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost


## 📊 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Feature Scaling
7. Model Training using Random Forest
8. Model Evaluation
9. Feature Importance Analysis
10. Save Trained Model (`best_model.pkl`)

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* Classification Report

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── Disease_Prediction.ipynb
├── Heart_Disease_data.csv
├── best_model.pkl
├── requirements.txt
└── README.md
```

## 🚀 Installation

```bash
git clone <repository-url>
cd Heart-Disease-Prediction
pip install -r requirements.txt
```

## ▶️ Usage

1. Open `Disease_Prediction.ipynb`.
2. Run all notebook cells.
3. Train the Random Forest model.
4. Save the trained model as `best_model.pkl`.
5. Use the saved model for predicting new patient data.

## 📌 Results

The Random Forest Classifier achieved strong performance in predicting heart disease and was selected as the final model based on evaluation metrics.

## 👨‍💻 Author

Aditya Vikram Singh


