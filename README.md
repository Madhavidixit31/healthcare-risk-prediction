# Healthcare Risk Prediction using Machine Learning

This project predicts cardiovascular disease risk based on patient health indicators. It's designed to demonstrate end-to-end data engineering and machine learning pipeline skills using real healthcare data.

## Dataset

**Source:** [Kaggle - Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)  
- 70,000 patient records  
- Features include age, gender, blood pressure, cholesterol, glucose, lifestyle factors, and a binary target (`cardio`).

## Project Objectives

- Clean, process, and harmonize healthcare data
- Engineer relevant features (e.g., age in years, BMI)
- Build predictive models to classify cardiovascular disease risk
- Evaluate model performance and extract feature importance
- Prepare a machine learning ready dataset and visualize results

---

## 🧰 Tools & Technologies Used

| Area                  | Tools/Technologies                  |
|-----------------------|-------------------------------------|
| Programming           | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Machine Learning      | Scikit-learn (Logistic Regression, Random Forest) |
| Data Engineering      | Pandas, Feature Engineering |
| Visualization         | Matplotlib, Seaborn |
| Deployment/Versioning | GitHub                         |

---

## Project Include

### 1. `01_EDA`
- Dataset loading
- Basic profiling
- Visualization of target variable
- Correlation heatmap

### 2. `02_Cleaning_Feature_Eng`
- Convert `age` from days to years
- Calculate `BMI` from height and weight
- Remove outliers (blood pressure, height, weight)
- Save a clean dataset for ML modeling

### 3. `03_Model_Training`
- Train/test split
- Logistic Regression baseline model
- Random Forest with feature importance
- Evaluation: confusion matrix, ROC curve, classification report

---

## Key Findings

- **Top Features Influencing Risk**: Age, BMI, Systolic BP, Cholesterol
- **Random Forest** outperformed Logistic Regression in ROC-AUC and recall
- Clean data and proper feature scaling significantly improved results

---

## 📌 Future Work

- Hyperparameter tuning using GridSearchCV
- Deploy model via FastAPI or Flask
- Build dashboard (Power BI or Streamlit) for clinical visualization
- Explore temporal/longitudinal health records

---


