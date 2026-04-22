# 🏠 House Price Prediction using Model Validation & Hyperparameter Tuning

## 📌 Overview
This project focuses on improving a house price prediction model by applying key machine learning techniques such as overfitting detection, cross-validation, and hyperparameter tuning.

The goal is to build a model that not only performs well on training data but also generalizes effectively to unseen data.

---

## 📊 Dataset
- California Housing Dataset (from scikit-learn)

Features include:
- Median Income
- House Age
- Average Rooms
- Population
- Occupancy
- Latitude & Longitude

Target variable: Median House Price

---

## 🛠️ Tools & Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Models Used
- Linear Regression (Baseline)
- Ridge Regression (Regularized)
- Decision Tree Regressor (Overfitting Analysis)
- Tuned Decision Tree (Final Model)

---

## ⚙️ Techniques Applied
- Data Preprocessing & Feature Scaling
- Train-Test Split (80:20)
- Overfitting Detection (Train vs Test Performance)
- 5-Fold Cross Validation
- Hyperparameter Tuning using GridSearchCV

---

## 📊 Final Results

| Model               | RMSE   | R² Score |
|--------------------|--------|----------|
| Linear Regression  | 0.7456 | 0.5758   |
| Ridge Regression   | 0.7456 | 0.5758   |
| Tuned Decision Tree| 0.6389 | 0.6885   |

👉 The Tuned Decision Tree achieved the best performance by reducing overfitting and improving generalization.

---

## 📉 Insights
- Decision Tree initially overfitted the data (very low training error, high test error)
- Cross-validation provided more reliable model evaluation
- Hyperparameter tuning significantly improved model performance

---

## 📂 Project Files
- 📓 Notebook: `Task3_Model_Validation.ipynb`
- 📄 Report: `Task3_Model_Validation_Report.pdf`

---

## 🚀 How to Run
1. Clone the repository
2. Open the notebook in Jupyter Notebook
3. Run all cells to reproduce results

---

## 📚 Key Learnings
- Importance of detecting and controlling overfitting
- Role of cross-validation in reliable evaluation
- Impact of hyperparameter tuning on model performance
- Model selection should focus on generalization, not just accuracy

---

⭐ This project was completed as part of an AI/ML Internship Task.
