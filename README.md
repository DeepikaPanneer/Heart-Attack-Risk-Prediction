# ❤️ Heart Attack Risk Prediction

This project aims to build a machine learning model that can **predict the risk of a heart attack** in individuals based on various medical and lifestyle factors. The goal is to assist in early diagnosis and enable timely interventions using predictive analytics.

---

## 🩺 Project Objective

To accurately evaluate whether a person is at risk of a heart attack by analyzing their health records using machine learning classification models.

---

## 📊 Dataset Information

- 📁 **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset)
- 📌 **Total Records**: 8,763 patients
- 🔢 **Features**: 25 independent variables and 1 target variable
- ❌ **Preprocessing Steps**:
  - Removed Patient ID column
  - Split "Blood Pressure" into Systolic and Diastolic
  - Handled null values and duplicates

### ⚙️ Key Features:
- Age, Sex, Cholesterol, Blood Pressure, Heart Rate
- Diabetes, Family History, Smoking, Obesity
- Exercise, Diet, Alcohol Consumption, Medication Use
- Stress Level, Sleep Hours, Sedentary Hours, BMI
- Country, Income, Physical Activity, Triglycerides

---

## 🔬 Algorithms Used

We tested five popular classification models:

| Algorithm              | Accuracy (%) |
|------------------------|--------------|
| Logistic Regression    | **72.09**     |
| Random Forest          | 70.62        |
| Naive Bayes            | 64.18        |
| SVM (Linear Kernel)    | 64.18        |
| Decision Tree          | 64.06        |

### ✅ Evaluation Metrics
- Accuracy
- Classification Report
- Confusion Matrix

---

## 🧠 Conclusion

- Logistic Regression achieved the highest accuracy at **72.09%**.
- Random Forest also performed well, followed by other models.
- The model shows promise for real-world health risk prediction and awareness.

---

## 🔭 Future Work

- Integrate **larger and more diverse datasets** for better generalization.
- Explore **deep learning** methods to capture hidden risk patterns.
- Include **real-time wearable device data** and **genetic information** for personalized risk analysis.

