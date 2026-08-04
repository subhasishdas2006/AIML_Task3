# 🏠 House Price Prediction – Task 3: Model Validation, Overfitting Control & Hyperparameter Tuning

## 📌 Project Overview

This project demonstrates how to improve machine learning model performance using model validation techniques, overfitting control, and hyperparameter tuning.

The California Housing dataset from scikit-learn is used to predict median house prices. Multiple regression models are trained and compared using evaluation metrics such as RMSE and R² Score.

---

## 🎯 Objectives

* Perform Train-Test Split
* Apply Cross-Validation
* Detect Overfitting
* Perform Hyperparameter Tuning using GridSearchCV
* Compare different regression models
* Save the best-performing model

---

## 📂 Dataset

**California Housing Dataset**

Source:

* scikit-learn.datasets.fetch_california_housing()

Features include:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

Target:

* Median House Value

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* Joblib

---

## 📊 Models Used

1. Linear Regression
2. Decision Tree Regressor
3. Tuned Decision Tree Regressor (GridSearchCV)

---

## 📈 Evaluation Metrics

* Root Mean Squared Error (RMSE)
* R² Score
* 5-Fold Cross Validation

---

## ⚙ Hyperparameter Tuning

GridSearchCV was used to optimize:

* max_depth
* min_samples_split
* min_samples_leaf

---

## 📁 Project Structure

AI_ML_Task3/

* task3_model_validation.ipynb
* best_model.pkl
* requirements.txt
* README.md
* Task3_Report.pdf



---

## 📌 Results

* Compared Linear Regression and Decision Tree models.
* Applied Cross-Validation for reliable evaluation.
* Reduced overfitting using GridSearchCV.
* Selected the best-performing model based on RMSE and R² Score.
* Saved the final trained model using Joblib.

---

## 🚀 Future Improvements

* Random Forest Regressor
* Gradient Boosting
* XGBoost
* Feature Engineering
* Feature Selection
* Model Deployment using Flask or FastAPI

---
## Results and Conclusion

Three regression models were trained and evaluated using the California Housing dataset. Linear Regression served as the baseline model, achieving an RMSE of **0.745581** and an R² Score of **0.575788**. A Decision Tree Regressor improved the performance, reducing the RMSE to **0.709301** and increasing the R² Score to **0.616068**.

To further improve performance and reduce overfitting, GridSearchCV was used to tune the Decision Tree's hyperparameters. The tuned Decision Tree achieved the best results, with an RMSE of **0.639065** and an R² Score of **0.688338**. Compared to the baseline model, the tuned model produced more accurate predictions and explained a greater proportion of the variance in house prices.

Overall, the results demonstrate that model validation through cross-validation and hyperparameter tuning significantly improves machine learning model performance. The Tuned Decision Tree Regressor was selected as the final model because it achieved the lowest prediction error and the highest R² Score among all the evaluated models.


