# Superconductor Critical Temperature Prediction

This project applies data mining techniques to predict the **critical temperature** of superconductors using the [Superconductivity dataset](https://archive.ics.uci.edu/ml/datasets/Superconductivty+Data) from the UCI Machine Learning Repository. It is a regression problem completed as part of a university group assignment for the *Big Data Mining Techniques* module.

---

## 📊 Dataset

The dataset contains information on **21,263 superconductors**, with **81 numerical features** and one target variable: `critical_temperature`.

- **train.csv** – Contains the main feature set with critical temperature values
- **unique_m.csv** – Contains the chemical formulas (not used in this task)

Reference: [Sathishkumar et al., Building Research & Information](https://www.uow.edu.au/library/)

---

## 🎯 Objective

Implement a full end-to-end regression pipeline using **Scikit-learn** to:
- Discover and visualize data patterns
- Prepare features and engineer new ones
- Train and tune multiple regression models
- Evaluate and compare performance

---

## 🛠️ Project Workflow

1. **Data Preparation**
   - Applied **stratified sampling** to split the dataset: 80% training, 20% testing
   - Performed data cleaning, scaling, and initial feature inspection

2. **Feature Engineering**
   - Developed a **User-Defined Transformer** to create a new custom feature
   - Transformer includes a parameter to toggle inclusion for hyperparameter tuning

3. **Model Training**
   - Trained the following regression algorithms:
     - **Linear Regression**
     - **Random Forest Regressor**
     - **Gradient Boosting Regressor**

4. **Model Tuning**
   - Used **GridSearchCV** for hyperparameter optimization
   - Tuned models both with and without the new feature

5. **Evaluation**
   - Evaluated models using **Root Mean Square Error (RMSE)** and cross-validation scores
   - Compared performance across models to determine best fit

---

## 📈 Results

All steps are implemented in a **single Jupyter Notebook** with markdown explanations and visualizations for full reproducibility.

---

## 📌 Notes

This project was completed as **Task 1** of a university data mining assignment. It demonstrates familiarity with regression modeling, custom pipeline construction, hyperparameter tuning, and reproducible scientific reporting using Python.

