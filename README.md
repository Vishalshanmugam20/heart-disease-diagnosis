# Heart Disease Clinical Diagnosis System

This project is a Machine Learning-based clinical diagnosis system designed to predict the presence of heart disease. It utilizes a multivariate dataset to analyze patient health metrics and provide early diagnostic insights.

## 📊 Dataset Overview
The project uses the **[UCI Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)**, a classic resource in the ML community. While the original database contains 76 attributes, this system focuses on the published subset of **14 key clinical features**:

### Column Descriptions:
1.  **age**: Age of the patient (years).
2.  **sex**: Male/Female.
3.  **cp**: Chest pain type (typical angina, atypical angina, non-anginal, asymptomatic).
4.  **trestbps**: Resting blood pressure (in mm Hg).
5.  **chol**: Serum cholesterol (mg/dl).
6.  **fbs**: Fasting blood sugar > 120 mg/dl (True/False).
7.  **restecg**: Resting electrocardiographic results.
8.  **thalach**: Maximum heart rate achieved.
9.  **exang**: Exercise-induced angina (True/False).
10. **oldpeak**: ST depression induced by exercise relative to rest.
11. **slope**: The slope of the peak exercise ST segment.
12. **ca**: Number of major vessels (0-3) colored by fluoroscopy.
13. **thal**: Thalassemia status (normal; fixed defect; reversible defect).
14. **num**: The predicted attribute (Diagnosis of heart disease).

## 🛠️ Project Workflow
* **Exploratory Data Analysis (EDA)**: Understanding data distributions and correlations.
* **Preprocessing**: Handling missing values and categorical encoding.
* **Model Selection**: Testing various classifiers including Logistic Regression and XGBoost.
* **Evaluation**: Measuring performance via Accuracy, Precision, and Recall.
