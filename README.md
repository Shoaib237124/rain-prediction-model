# Rainfall Prediction Model 🌧️

This project focuses on building a machine learning model to predict rainfall using weather data. The model was trained on a dataset collected from Kaggle and includes steps like data cleaning, exploratory data analysis (EDA), preprocessing, model training, and evaluation.

---

## 📁 Dataset

- Source: Kaggle
- Contains weather-related features such as:
  - Pressure
  - Dew Point
  - Humidity
  - Cloud Cover
  - Sunshine
  - Wind Direction
  - Wind Speed

---

## 🧹 Data Preprocessing

- Removed outliers and handled missing values
- Performed Exploratory Data Analysis (EDA)
- Handled class imbalance using **downsampling** technique from `resample` (imbalanced-learn)

---

## ⚙️ Model Building

- Split data into training and testing sets
- Used **GridSearchCV** to tune hyperparameters and compare the following models:
  - Support Vector Classifier (SVC)
  - Logistic Regression
  - Random Forest

✅ **Best performing model**: Random Forest

---

## 📊 Model Evaluation

- Evaluated model using:
  - **Classification Report**
  - **Confusion Matrix**
- Accuracy was highest on the Random Forest model

---

## 💾 Deployment

- Saved the final trained model using **Pickle** (`.pkl`)
- Model was tested on **unseen input data** for prediction




