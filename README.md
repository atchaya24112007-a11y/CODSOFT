# Titanic Survival Prediction 🚢

This project predicts whether a passenger survived the Titanic disaster using Machine Learning.  
It was completed as part of my **CodSoft Internship**.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that predicts passenger survival based on features such as age, gender, ticket class, fare, and embarkation port.

---

## 📊 Dataset

- Dataset downloaded from **Kaggle**
- File used: `titanic.csv`
- Contains passenger details like:
  - Pclass
  - Sex
  - Age
  - Fare
  - Embarked
  - Survived

---

## 🛠 Tools & Technologies Used

- Python  
- VS Code  
- Pandas  
- Scikit-learn  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Imported the Titanic dataset into Python using Pandas.

### 2️⃣ Data Cleaning & Preprocessing
- Filled missing values in the **Age** column using the mean.
- Removed the **Cabin** column due to too many missing values.
- Filled missing values in **Embarked** using the most frequent value.
- Converted categorical data into numerical form:
  - Embarked:
    - S → Southampton
    - C → Cherbourg
    - Q → Queenstown  
    - Converted to numeric values (0, 1, 2) for machine learning.

### 3️⃣ Feature Selection
- Selected important features such as:
  - Passenger class
  - Age
  - Gender
  - Fare
  - Embarkation port

### 4️⃣ Model Building
- Split the dataset into training and testing sets.
- Trained a **Logistic Regression** model using Scikit-learn.

### 5️⃣ Model Evaluation
- Evaluated the model using **accuracy score**.

---

## ✅ Result

- The model achieved a good accuracy in predicting passenger survival.
- This project helped me understand the **end-to-end Machine Learning workflow**.

---

## 📂 Files in This Repository

- `Titanic_Survival_Prediction.py` – Main Python file  
- `titanic.csv` – Dataset file  
- `README.md` – Project documentation  

---

## 🚀 Conclusion

This beginner-friendly project strengthened my understanding of data preprocessing, feature engineering, and machine learning model building using Python.

---

⭐ If you like this project, feel free to star the repository!
