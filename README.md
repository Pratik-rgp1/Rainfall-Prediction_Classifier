# 🌧️ Rainfall Prediction Classifier

## 📌 Project Overview

This project is part of a final lab assignment focused on building a **machine learning classifier** to predict whether it will rain today. Using real-world weather data, we develop a robust pipeline, perform feature engineering, compare multiple models, and evaluate performance using various classification metrics.

> **Objective**: Predict "RainToday" as a binary classification problem using both Logistic Regression and Random Forest, and compare their effectiveness.

---

## 🧠 Learning Outcomes

After completing this project, you will be able to:

- Explore and perform feature engineering on a real-world dataset.
- Build and optimize a machine learning pipeline using `Pipeline` and `GridSearchCV`.
- Evaluate model performance with accuracy, precision, recall, F1-score, and confusion matrix.
- Switch between different classifiers like Logistic Regression and Random Forest.
- Visualize feature importances and compare model performances.

---
## 📊 Model Comparison Summary

### ✅ Logistic Regression

- **Accuracy**: 83%
- **Precision (Rain)**: 0.69
- **Recall (Rain)**: 0.51
- **F1-score (Rain)**: 0.59
- **True Positives (Rain)**: 184 / 358

### ✅ Random Forest Classifier

- **Accuracy**: 84%
- **Precision (Rain)**: 0.75
- **Recall (Rain)**: 0.51
- **F1-score (Rain)**: 0.61
- **True Positives (Rain)**: 183 / 358

> 🔍 **Conclusion**:
> - Random Forest slightly outperforms Logistic Regression in overall accuracy and precision.
> - Both models have identical recall (0.51), but Random Forest has a better F1-score.
> - Logistic Regression detected 1 more rainy day correctly but had more false positives.

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/rainfall-prediction-classifier.git
   cd rainfall-prediction-classifier

