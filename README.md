# Loan Default Prediction 🚀

This project is part of the final course project for advanced business analytics. The goal is to predict loan default status using historical customer data and apply Random Forest and Support Vector Machine (SVM) classification techniques.

## 📁 Files

- `Advanced_Business_Analytics_Final_Project.ipynb`: The cleaned and structured notebook.
- `sample_submission.csv`: Final prediction output submitted to Kaggle.
- `train.csv`, `test.csv`: Training and test datasets used in the project (not included here for privacy reasons).

## 📌 Objective

To accurately predict whether a customer will default on a loan using features like:
- Age, Gender, Marital Status
- Education, Occupation, Income
- Loan info, Credit Score, Payment History

## ⚙️ Methods Used

- Checking Class Imbalance
- IQR Method for Class Imbalance
- Capping and Flooring
- Label Encoding
- Random Forest
- Support Vector Classifier (SVM)
- ROC Curve, AUC Score
- Train/Test Split and Evaluation

## 📊 Results

- **Validation Accuracy**: ~0.79 (SVM)
- ROC AUC: ~0.86
- Observations: The model handled the majority class well, but underperformed on the minority class. Further improvement could involve SMOTE or class weighting.

## ✅ Future Improvements

- Try other models (XGBoost, Adaboost etc)
- Apply cross-validation
- Handle class imbalance with techniques like SMOTE or ADASYN

## ⚠️ Disclaimer

This project was created as part of an academic course and may include content or datasets that are subject to copyright or terms of use restrictions. The notebook and any associated files are shared for educational purposes only. Redistribution, modification, or commercial use is not permitted without explicit permission.

