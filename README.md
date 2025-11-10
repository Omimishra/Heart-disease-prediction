# Heart Disease Prediction🫀

Heart disease remains one of the leading causes of death worldwide, making early detection crucial for timely treatment and prevention. This project leverages deep learning technique to predict the likelihood of heart disease in patients based on key medical attributes such as age, cholesterol level, resting blood pressure, and maximum heart rate achieved. A **Neural Network** **built with Keras and TensorFlow** is trained to classify patients as at risk or not, following a full data science workflow — from **data cleaning and EDA** to **model training and evaluation**.
The goal is to assist healthcare professionals with **data-driven risk assessment** and **early detection** of heart disease.

## Team Members🎯
- Omi Mishra : 202210101150027
- Srishti Tripathi : 202210101150024

## Model (summary) ⚙️
This section summarizes the modeling work done in the project.
- Approach
  - Goal: Predict presence/absence of heart disease using clinical and diagnostic features.
  - Typical pipeline: data cleaning → feature engineering → feature scaling/encoding → model training → model evaluation

- Features
  - Uses clinical features present in the dataset (age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG results, max heart rate achieved, exercise-induced angina, ST depression, slope of ST, number of major vessels colored by fluoroscopy, thalassemia, etc.).
  - All features were scaled when required by the model.

- Model Used
  - Sequential

- Evaluation metrics
  - Common metrics used: accuracy, precision, recall, f1 score and confusion matrices.
  - 86.81 accuracy

- Tech Stack
  - Python, pandas, numpy
  - Seaborn, matplotlib
  - Tensorflow,kears,scikit learn
    
## Contents📜
- Jupyter notebook: model.ipynb file
- heart_disease_prediction.csv
- requirements.txt

