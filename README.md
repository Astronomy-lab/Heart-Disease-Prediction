# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project predicts the likelihood of heart disease using patient medical data and Machine Learning. It follows a complete ML pipeline including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction. The Random Forest Classifier was selected as the final model based on its performance.

---

## 🎯 Objective
To build a machine learning model that accurately predicts whether a patient has heart disease using clinical and medical attributes.

---

## 📊 Dataset
- **Dataset:** UCI Heart Disease Dataset
- **Source:** UCI Machine Learning Repository
- **Records:** 303 Patients
- **Target Variable:** `num` (converted into binary target)
  - **0** → No Heart Disease
  - **1** → Heart Disease

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib
- Streamlit

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── app.py
├── Data/
│   └── Heart_Disease_data.csv
│
├── Images/
│   ├── age_distribution.png
│   ├── disease_distribution.png
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── Models/
│   └── best_model.pkl
│
├── notebooks/
│   └── Disease_Prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Missing Value Handling
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Feature Importance Analysis
11. Save Best Model
12. Streamlit Web Application

---

## 🤖 Machine Learning Models

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest ✅ (Selected Model)
- XGBoost

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
```

Go to the project folder:

```bash
cd Heart-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 💻 Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Heart disease prediction
- Random Forest model
- Feature importance visualization
- Interactive Streamlit interface
- Saved trained model (`best_model.pkl`)

---

## 🔮 Future Improvements

- Improve model accuracy using hyperparameter tuning.
- Deploy the application on Streamlit Community Cloud.
- Add support for multiple disease prediction.
- Integrate real-time patient data.
- Enhance the user interface.

---

## 👨‍💻 Author

**Aditya Vikram Singh**


