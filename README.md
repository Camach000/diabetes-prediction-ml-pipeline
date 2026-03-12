# 🩺 Medical Diagnosis: Machine Learning Pipeline for Diabetes

> An end-to-end machine learning pipeline built to predict the onset of diabetes based on diagnostic measures, utilizing the Pima Indians dataset.

## 🧠 About the Project

This project focuses on building a robust binary classification system with a strong emphasis on minimizing false negatives—a critical factor in medical diagnostics. The pipeline demonstrates a rigorous approach to handling imbalanced datasets and evaluating model reliability.

**Key Highlights:**
* **Data Preprocessing:** Implemented complete pipelines using `scikit-learn`, including robust missing data handling (Imputation) and feature scaling (`StandardScaler`).
* **Model Evaluation:** Ensured statistical reliability on imbalanced data by applying **Stratified K-Fold Cross-Validation**.
* **Algorithm Comparison:** Rigorously compared the performance of Random Forest and Logistic Regression models.
* **Results:** Achieved an **F1-Score of ~77%** in the positive class through hyperparameter optimization via `GridSearchCV`.

## 📂 Repository Contents

* `pimaDiabetes.ipynb`: The main Jupyter Notebook containing the full pipeline (Exploratory Data Analysis, preprocessing, model training, and evaluation).
* `pimaDiabetes.html`: An exported HTML version of the notebook for quick and easy viewing directly in any web browser.
* `pimaDiabetes.p`: The serialized (pickled) trained model, ready for deployment or fast inference.

## 🛠️ Tech Stack

* **Language:** Python
* **Machine Learning:** Scikit-learn
* **Data Manipulation:** Pandas, NumPy
* **Environment:** Jupyter Notebook

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/diabetes-prediction-ml-pipeline.git](https://github.com/your-username/diabetes-prediction-ml-pipeline.git)
