# GoalZone Fitness Club – Class Attendance Prediction

## 📊 Project Overview

This project explores predictive analytics for class attendance at a fitness club, using the **GoalZone dataset**. The objective is to analyze member behavior, identify key patterns, and build machine learning models that accurately predict whether a member will attend a class.

This work was submitted as part of the **Applied Data Analytics** module.

---

## 🎯 Objectives

- Understand trends in class attendance.
- Explore relationships between member attributes and attendance.
- Preprocess and transform the data for modeling.
- Build and evaluate three different machine learning models.
- Recommend the best-performing model for practical use.

---

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn** (Logistic Regression, Random Forest, K-Nearest Neighbors)
- **CRISP-DM** Methodology

---

## 📂 Project Structure

- `GoalZone_CA2AppliedDataAnalytics_YvanaOliveira.ipynb`: Main notebook with data analysis, preprocessing, modeling, and evaluation.
- `README.md`: This file.

---

## 📈 Key Features
Exploratory Data Analysis (EDA)

Data Cleaning and Feature Engineering

Binary Classification (Attendance vs. No-Show)

Model Comparison based on Accuracy and Confusion Matrix

Clear insights and final recommendation

---

## 📌 Key Findings
Previous No-Shows is a strong predictor of future attendance – members who previously missed classes are more likely to do so again.

Member Type, Visit Time, and Class Type were also associated with attendance behavior.

The dataset had a mild class imbalance, favoring attendance over no-show.

Among the three models tested:

Random Forest performed best with ~81% accuracy.

Logistic Regression achieved ~76% accuracy.

K-Nearest Neighbors underperformed due to sensitivity to high-dimensionality and class imbalance.

Random Forest is the recommended model due to its accuracy and reliability in identifying no-shows.

