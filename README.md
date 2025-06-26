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
## 🔍 Model Comparison

| Model            | Accuracy | F1 Score | ROC-AUC |
|------------------|----------|----------|---------|
| Logistic Reg     | 0.899    | 0.55     | 0.88    |
| KNN              | 0.928    | 0.71     | 0.87    |
| Decision Tree    | 0.911    | 0.70     | 0.83    |
| Random Forest    | 0.949    | 0.79     | 0.93    |
| XGBoost          | 0.951    | 0.81     | 0.95    |
| CatBoost         | 0.953    | 0.82     | 0.96    |
| LightGBM         | 0.952    | 0.81     | 0.96    |

CatBoost had the highest ROC-AUC and F1 Score among all models.
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
