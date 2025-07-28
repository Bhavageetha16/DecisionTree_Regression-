# 📊 Decision Tree Regression – Salary Prediction Based on Position Level

## 📝 Project Overview

This project demonstrates how to use **Decision Tree Regression** to predict an employee's salary based on their position level. It showcases the use of a non-linear regression model to better capture the structure of the data where linear models might fail.

---

## 🔍 Problem Statement

Given a dataset of employee positions with corresponding levels and salaries, the objective is to predict the salary of a new employee using their position level as input.

---

## 📂 Dataset Description

The dataset used is `Position_Salaries.csv` and contains the following columns:

| Column     | Description                          |
|------------|--------------------------------------|
| Position   | Job title (e.g., Analyst, Manager)   |
| Level      | Numeric level of the position        |
| Salary     | Annual salary for the position       |

Example entries:

Business Analyst 1 45000
Junior Consultant 2 50000
Senior Manager 7 200000
CEO 10 1000000

## ⚙️ Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🧠 Steps to Implement

1. **Import Libraries**
2. **Load Dataset**
3. **Extract Independent (`X`) and Dependent (`y`) Variables**
4. **Train the Decision Tree Regressor**
5. **Predict a New Result (e.g., Level 6.5)**
6. **Visualize the Results in High Resolution**

---

## 📈 Visualization

The result is visualized using `matplotlib`:
- Red dots: Actual data points (Level vs Salary)
- Blue line: Model predictions over a high-resolution grid of `Level` values to show step-like predictions made by the decision tree.

---

## 🧪 Example Prediction

```python
regressor.predict([[6.5]])
# Output (e.g.): array([150000.])
pip install numpy pandas matplotlib scikit-learn


