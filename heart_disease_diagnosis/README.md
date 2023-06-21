# Heart Disease Diagnosis Project

This algorithm is designed to analyze a patiant's physical and clinical health indicators to determine whether the individual is suffering from a heart disease. The project relies on a number of statistical analyses as well as machine learning and deep learning algorithms to accurately predict outcomes and provide valuable insights.

## Data Overview

The data is accessed via an open source repository on [kaggle.com](https://www.kaggle.com/datasets/ritwikb3/heart-disease-cleveland). The database contains 13 attributes and a target variable. It has 8 nominal values and 5 numeric values. The detailed description of all these features are as follows:

Age: Patients Age in years (Numeric)
Sex: Gender (Male : 1; Female : 0) (Nominal)
    cp: Type of chest pain experienced by patient. This term categorized into 4 category.
    0 typical angina, 1 atypical angina, 2 non- anginal pain, 3 asymptomatic (Nominal)
    trestbps: patient's level of blood pressure at resting mode in mm/HG (Numerical)
    chol: Serum cholesterol in mg/dl (Numeric)
    fbs: Blood sugar levels on fasting > 120 mg/dl represents as 1 in case of true and 0 as false (Nominal)
    restecg: Result of electrocardiogram while at rest are represented in 3 distinct values
    0 : Normal 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of >
    0.05 mV) 2: showing probable or definite left ventricular hypertrophyby Estes' criteria (Nominal)
    thalach: Maximum heart rate achieved (Numeric)
    exang: Angina induced by exercise 0 depicting NO 1 depicting Yes (Nominal)
    oldpeak: Exercise induced ST-depression in relative with the state of rest (Numeric)
    slope: ST segment measured in terms of slope during peak exercise
    0: up sloping; 1: flat; 2: down sloping(Nominal)
    ca: The number of major vessels (0–3)(nominal)
    thal: A blood disorder called thalassemia
    0: NULL 1: normal blood flow 2: fixed defect (no blood flow in some part of the heart) 3: reversible defect (a blood flow is observed but it is not normal(nominal)
    target: It is the target variable which we have to predict 1 means patient is suffering from heart disease and 0 means patient is normal.

## Machine Learning Models

The outcome of a number of different ML and DL algorithms are compared here. Inputting more data examples would very likely improve the results. Overall, I believe that the algorithms presented here work quite well for a relatively small dataset (303 individuals).

## Acknowledgement

I appreciate the addition of XGBoost algorithm due to #rfjd.
