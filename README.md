# Machine Learning Pipeline

A hands‑on notebook demonstrating how to build, evaluate, and optimize machine learning pipelines using **scikit‑learn**. The project walks through the complete workflow from exploratory data analysis (EDA) to model deployment, showcasing best practices for reproducible ML.

---

## 📌 Features

- **Exploratory Data Analysis (EDA)**  
  Basic statistics and feature engineering on the Iris dataset.

- **Data Preprocessing**  
  - Train‑test split with validation set  
  - Numerical pipeline: scaling with `StandardScaler`  
  - Categorical pipeline: encoding with `OrdinalEncoder`  
  - Unified preprocessing via `ColumnTransformer`

- **Model Pipelines**  
  Integrated pipelines combining preprocessing and classifiers:
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting  
  - AdaBoost

- **Model Evaluation**  
  - Accuracy scores on test and validation sets  
  - Cross‑validation for robust performance checks

- **Hyperparameter Tuning**  
  Grid search across multiple parameter grids for each model.

- **Model Persistence**  
  Save and load the best estimator using `pickle`.

---

## 🛠️ Tech Stack

- **Languages**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, scikit‑learn  
- **Environment**: Google Colab

---

## 🚀 Workflow Overview

1. Load dataset (`iris`)  
2. Perform EDA and feature engineering  
3. Split into train, validation, and test sets  
4. Build preprocessing pipelines  
5. Train multiple models with pipelines  
6. Evaluate with cross‑validation  
7. Tune hyperparameters using `GridSearchCV`  
8. Save the best model for deployment

---
```

---

## 📈 Results

- Decision Tree, Gradient Boosting, and Random Forest achieved high accuracy (up to **100%** on test/validation).  
- Hyperparameter tuning improved generalization, with Gradient Boosting emerging as the most consistent performer.  
- Final model saved as `iris_classifier.pkl` for reuse.

---

## 🔮 Next Steps

- Extend pipeline to larger, real‑world datasets  
- Add more preprocessing steps (missing values, feature selection)  
- Integrate with deployment frameworks (e.g., Streamlit, Flask)  
- Experiment with advanced models (XGBoost, LightGBM)

---

Would you like me to also draft a **requirements.txt** file for this repo so anyone cloning it can run the notebook immediately?
