# 🚢 Titanic Survival Prediction

## 👤 Author
**Subham Mondal**  
Department of Computer Science & Engineering (CSE)  

---

## 📌 Project Overview
This project predicts whether a passenger survived the **Titanic disaster** using **Machine Learning** techniques.  
The dataset is the classic [Titanic dataset](https://www.kaggle.com/c/titanic), which is widely used for beginner ML projects.

The workflow includes:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Model Training (Logistic Regression, Decision Tree, Random Forest, etc.)  
- Model Evaluation using accuracy and other metrics  

---

## 📂 Dataset
The dataset contains details of Titanic passengers such as:
- PassengerId, Pclass, Name, Sex, Age  
- SibSp, Parch, Ticket, Fare, Cabin, Embarked  
- **Survived** (Target: 0 = No, 1 = Yes)  

Files used:
- `train.csv` → Training data  
- `test.csv` → Testing data  
- `gender_submission.csv` → Sample submission  

---

## 🛠️ Approach
1. Data preprocessing (handle missing values, encode categorical features).  
2. Exploratory Data Analysis (visualizations, feature correlations).  
3. Model training with:
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Support Vector Machine (SVM)  
4. Evaluation using accuracy, confusion matrix, and F1-score.  

---

## 📊 Results
- Logistic Regression baseline ~78% accuracy.  
- Random Forest & Gradient Boosting ~80–85% accuracy.  
- Most important features: **Sex, Pclass, Age, Fare, Family size**.  

---



