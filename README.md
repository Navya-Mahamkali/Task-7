# Task-7
# Titanic Survival Prediction - Machine Learning Project

## 📌 Overview
This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning techniques. It demonstrates a complete pipeline including data preprocessing, feature engineering, model training, and evaluation.

---

## 📂 Dataset
- Dataset: Titanic Dataset
- Features include:
  - Age
  - Sex
  - Fare
  - Pclass
  - SibSp
  - Parch
  - Embarked
- Target Variable:
  - Survived (0 = No, 1 = Yes)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🔧 Steps Performed

### 1. Data Loading
- Loaded dataset using Pandas
- Inspected structure using `.head()`, `.info()`, `.describe()`

### 2. Data Cleaning
- Filled missing values:
  - Age → Median
  - Embarked → Mode
- Dropped unnecessary columns:
  - PassengerId, Name, Ticket, Cabin (if present)

### 3. Feature Engineering
- Categorical Encoding using OneHotEncoder
- Feature Scaling using StandardScaler

### 4. Train-Test Split
- 80% Training, 20% Testing
- Used stratification to maintain class balance

### 5. Model Training
- Algorithm: Logistic Regression
- Implemented using Scikit-learn Pipeline

### 6. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## 📊 Results
- Model successfully predicts survival probability
- ROC-AUC used for robust evaluation
- Balanced performance across precision and recall

---

## 📈 Outputs
- Confusion Matrix Plot
- ROC Curve Plot
- AUC Score

---

## 🎯 Learning Outcomes
- Understanding Binary Classification
- Data Preprocessing Techniques
- Model Evaluation Metrics
- Pipeline Implementation

---

## 🚀 Future Improvements
- Try advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Feature selection optimization

---

## 👩‍💻 Author
Navya Mahamkali
