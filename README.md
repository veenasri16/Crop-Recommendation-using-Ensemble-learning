

🌾 Crop Recommendation System Using Machine Learning Ensemble Models

#📌 Project Overview

The **Crop Recommendation System** is a machine learning-based application that predicts the most suitable crop for cultivation based on soil nutrients and environmental conditions. This project assists farmers and agricultural stakeholders in making data-driven decisions to improve crop productivity and optimize land utilization.

The system compares multiple machine learning algorithms and utilizes ensemble learning techniques to achieve higher prediction accuracy.

---

# 🎯 Objectives

- Predict the most suitable crop based on soil and climatic conditions.
- Compare the performance of different machine learning algorithms.
- Improve prediction accuracy using ensemble learning methods.
- Build a reliable and efficient crop recommendation model.

---

#📂 Dataset

**Dataset Name:** Crop Recommendation Dataset

### Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH Value
- Rainfall (mm)

### Target Variable

- Crop Label

The dataset contains agricultural parameters used to recommend the most appropriate crop.

---

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- CatBoost

---

## 🤖 Machine Learning Models Implemented

The following machine learning models were trained and evaluated:

- Random Forest Classifier
- XGBoost Classifier
- CatBoost Classifier
- Voting Ensemble Classifier
- Stacking Ensemble Classifier

---

## 📊 Workflow

1. Import Dataset
2. Data Exploration
3. Data Preprocessing
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Performance Evaluation
8. Model Comparison
9. Crop Prediction

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- Classification Report

---

## 📊 Model Comparison

| Model | Description |
|--------|-------------|
| Random Forest | Ensemble decision tree algorithm with bagging technique. |
| XGBoost | Gradient boosting algorithm optimized for speed and performance. |
| CatBoost | Gradient boosting algorithm that efficiently handles categorical features. |
| Voting Ensemble | Combines predictions from multiple models using majority voting. |
| Stacking Ensemble | Uses predictions of base models to train a meta-classifier for improved performance. |

---

## 📁 Project Structure

```
Crop-Recommendation-System/
│
├── Crop_recommendation.csv
├── Crop_Recommendation.ipynb
├── README.md
├── requirements.txt
└── saved_model.pkl
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Crop-Recommendation-System.git
```

Navigate into the project

```bash
cd Crop-Recommendation-System
```

Install required packages

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
catboost
joblib
```

---

## 📌 Results

- Successfully trained multiple machine learning models.
- Compared their prediction performances.
- Ensemble learning techniques improved the overall prediction accuracy.
- The Voting and Stacking Ensemble models demonstrated strong predictive performance for crop recommendation.

---

## 🚀 Future Enhancements

- Deploy the model using Streamlit or Flask.
- Integrate real-time weather API.
- Add fertilizer recommendation.
- Develop a mobile application for farmers.
- Integrate GPS-based location services.

---

## 👩‍💻 Author

Veenasree

Artificial Intelligence Engineering Student

GitHub: https://github.com/veenasri16

LinkedIn: https://www.linkedin.com/in/varadaboina-veenasri-2566b434
