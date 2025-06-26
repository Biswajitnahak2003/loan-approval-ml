# Loan Approval Prediction

This is a machine learning project focused on predicting whether a loan application will be approved or not.  
i used various classification models and compared their performance.

---

## 📁 Project Structure

loan_approval_pred/
├── data/ ← Training and test datasets
├── logistic_regression/ ← Logistic Regression notebook
├── decision_tree/ ← Decision Tree notebook
├── k_nearest_neighbour/ ← KNN notebook
├── random_forest/ ← Random Forest notebook
├── xgb_regressor/ ← XGBoost notebook
├── catboost/ ← CatBoost notebook
├── lightgbm/ ← LightGBM notebook
├── comparison_of_all/ ← Model comparison CSV
├── final_model_ensemble.ipynb ← Ensemble/stacking notebook (WIP)
├── best_result_csv/ 
├── .gitignore
└── README.md


---

## 🧠 Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- XGBoost  
- CatBoost  
- LightGBM  

All models were evaluated based on:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## 📊 Dataset

Loan approval dataset from Kaggle competition(playground-series-s4e10).  
The dataset includes applicant info like income, employment, loan amount, intent, etc.

---

## 🥇 Current Best Model

CatBoost performed the best among all baseline models.  
Stacking/Voting and NN models I will be adding soon.

---

## 🚀 NEXT  (Coming Soon)

- Hyperparameter Tuning  
- Neural Network  
- Final ensemble with stacking/voting  


## 🙋‍♂️ Author

**Biswajit Nahak**  
[GitHub](https://github.com/Biswajitnahak2003)

---

## ⚙️ Requirements

Make sure you have the following installed:

```bash
scikit-learn
xgboost
catboost
lightgbm
matplotlib
pandas
numpy
jupyter
