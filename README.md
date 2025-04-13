# 🎓 Predicting Student Academic Performance using Non-Academic Factors (ML & DL)

This research project investigates the **impact of non-academic factors**—such as stress, sleep quality, motivation, screen time, and social support—on student academic performance using a combination of **Machine Learning (ML)** and **Deep Learning (DL)** models. Unlike traditional approaches that rely heavily on academic scores alone, this study explores the **predictive power of behavioral, psychological, and lifestyle features** through a hybrid modeling pipeline.

---

## 📁 Project Structure
```
   ├── data/ 
   │     └── student_performance_dataset_with_engineered_features.csv
   ├── notebooks/
   │      ├── 1_dataset_creation.ipynb
   │      ├── 2_feature_engineering.ipynb
   │      ├── 3_regression_models.ipynb
   │      ├── 4_classification_models.ipynb
   │      └── 5_deep_learning_models.ipynb
   ├── README.md
   └── requirements.txt
```

---

## 🧠 Models Used

### ✅ **Regression Models**
- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- Bayesian Ridge
- Random Forest Regressor
- Gradient Boosting Regressor

### 🧪 **Classification Models**
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)
- XGBoost Classifier
- LightGBM Classifier

### 🤖 **Deep Learning Models**
- Dense Neural Network (DNN)
- 1D Convolutional Neural Network (CNN)
- Hybrid RNN using LSTM + GRU

---

## 📊 Features Considered

- Age, Gender, Attendance
- Sleep Hours & Quality
- Motivation Score, Stress Level
- Screen Time, Social Support
- Study Environment Rating
- Commute Time, Room Sharing
- Physical Activity Days
- Part-time Job Status
- Household Size, Family Income
- Derived features like:
  - `stress_sleep_ratio`
  - `motivation_stress_diff`
  - `rest_quality_score`
  - `time_drain_score`
  - `mental_health_index`
  - `room_disturbance_score`

---

## 📈 Results Summary

- 📌 **Best Regression Model**: Gradient Boosting Regressor – R² ≈ **0.96**
- 📌 **Best Classification Model**: SVM & MLP – Accuracy ≈ **96.2%**
- 📌 **Best DL Model**: DNN – Accuracy ≈ **96.34%**
- 🔥 **Hybrid RNN (LSTM + GRU)** captured behavioral sequence dependencies effectively, enhancing practical applicability for educational data mining.

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
pip install -r requirements.txt
