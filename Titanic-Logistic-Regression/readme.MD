# 🚢 Titanic Survival Prediction using Logistic Regression

## 📌 Project Overview
This project uses Logistic Regression to predict whether a passenger survived the Titanic disaster based on features like age, gender, passenger class, and fare.

---

## 🎯 Objective
To build a classification model that predicts survival (0 = No, 1 = Yes) using machine learning techniques.

---

## 📊 Dataset
- Dataset: Titanic dataset (loaded from Seaborn library)
- Total records: 891 passengers
- Features used:
  - pclass (Passenger class)
  - sex (Gender)
  - age
  - fare
  - embarked (Port of embarkation)

---

## 🛠️ Steps Performed

### 1. Data Preprocessing
- Selected relevant features
- Handled missing values:
  - Age → filled with median
  - Embarked → filled with mode
- Converted categorical data:
  - Sex → male (0), female (1)
  - Embarked → one-hot encoding

---

### 2. Model Building
- Used Logistic Regression from Scikit-learn
- Split dataset into training (80%) and testing (20%)

---

### 3. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 📈 Results
- Model Accuracy: ~75%–85%
- The model performs well in predicting survival outcomes.

---

## 🔍 Key Insights
- Female passengers had a higher survival rate
- Passengers in higher classes (1st class) were more likely to survive
- Fare has a strong influence on survival probability
- Age has moderate impact on survival

---

## 🧰 Tools & Technologies
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## 🚀 Conclusion
Logistic Regression is effective for binary classification problems like survival prediction. Data preprocessing and feature selection play a key role in improving model performance.

---

## 📁 Project Structure