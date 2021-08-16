# Prediction-Stroke-Patients-
## Context
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

## Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not

## Conclusion
We had to deal with imbalanced data which is common in such healthcare problems. For improving the model we could try out other ways of dealing with imbalanced data like <b>SMOTE</b>.
We created 3 classifier with Decision Tree,Logistic Regression and Random Forest to forecast weather a patient can have stroke or not.<b>Random Forest with F-score=0.99</b>,<b>Decision Tree with F-score=0.98<b>and </b>Logistic Regression with F-score= 0.72.</b>
Most effective features on models are <b>age</b> around 46% importance, <b>avg_glucose_level</b> around 18% importance, <b>bmi</b> around 11% importance.
