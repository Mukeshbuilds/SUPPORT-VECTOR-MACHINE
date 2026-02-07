# SUPPORT-VECTOR-MACHINE
A simple Machine Learning project that predicts salary based on years of experience using Support Vector Regression (SVR). The model is trained on real salary data, evaluated with R² score, and saved using pickle for future predictions. Great beginner project to understand regression, model training, testing, and deployment basics.
# Salary Prediction using Support Vector Regression (SVR)

This project demonstrates how to build a Machine Learning regression model that predicts a person's salary based on their years of experience using **Support Vector Regression (SVR)** from Scikit-learn.

It is a beginner-friendly project that covers the complete ML workflow:
data loading → training → testing → evaluation → model saving → prediction.

---

## Dataset

The dataset used is `Salary_Data.csv`, which contains two columns:

- **YearsExperience** – Number of years of experience
- **Salary** – Corresponding salary

---

## Technologies Used

- Python
- Pandas
- Scikit-learn (SVR)
- Pickle (for model saving)

---

## 🚀 Project Workflow

1. Load the dataset using Pandas
2. Split data into training and testing sets
3. Train a **Support Vector Regression (SVR)** model with a linear kernel
4. Evaluate the model using **R² score**
5. Save the trained model using **pickle**
6. Load the model and make salary predictions for new inputs

---

##  Model Details

- Algorithm: **Support Vector Regression (SVR)**
- Kernel: Linear
- Test Size: 30%
- Evaluation Metric: R² Score

---

## Model Saving

The trained model is saved as: finalized_model_SLR.sav

