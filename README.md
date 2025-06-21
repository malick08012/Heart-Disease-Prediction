# Heart-Disease-Prediction
A machine learning project that predicts the risk of heart disease based on patient health data. Includes data cleaning, EDA, visualization, model training, evaluation and feature importance analysis

🎯 Task Objective:

To build a machine learning model that predicts whether a person is at risk of heart disease based on their medical and health-related attributes. The goal is to support early detection and decision-making in healthcare using interpretable models.

📂 Dataset Used:

Dataset: Heart Disease UCI Dataset

The dataset contains 14 attributes per patient, such as age, cholesterol, chest pain type, ECG results, and more.

All missing values were handled, and duplicate entries were removed for quality assurance.

📳 Model Applied:

Logistic Regression: The primary model used due to its simplicity and interpretability.

📈 Key Results & Findings:

Logistic Regression Performance:

Accuracy: 82%

AUC Score: 0.87

Confusion Matrix and ROC Curve showed reliable performance in distinguishing between at-risk and healthy individuals.

Top Influential Features:

1. chest_pain_type_Typical angina (protective factor)

2. vessels_colored_by_flourosopy_Zero (strong risk factor)

3. thalassemia_Reversable Defect, oldpeak, and rest_ecg_ST-T wave abnormality also played significant roles.

EDA Insights:

1. Patients with typical angina or normal thalassemia had lower risk.

2. Higher oldpeak values were linked to heart disease.

3. Distributions and boxplots helped reveal patterns and outliers.



