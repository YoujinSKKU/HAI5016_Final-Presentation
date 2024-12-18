# Diabetes Prediction

Predict Diabetes with Medical & Demographic Data

![header](https://www.cdc.gov/diabetes/news/media/images/Diabetesaboutpage.jpg)

## About Dataset

  **Data Description**:
  The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.

  **Attribute Information**:

- gender: Gender refers to the biological sex of the individual, which can have an impact on their susceptibility to diabetes. There are three categories in it male ,female and other.
- age: Age is an important factor as diabetes is more commonly diagnosed in older adults.Age ranges from 0-80 in our dataset.
- hypertension: Hypertension is a medical condition in which the blood pressure in the arteries is persistently elevated. It has values a 0 or 1 where 0 indicates they don’t have hypertension and for 1 it means they have hypertension.
- heart_disease: Heart disease is another medical condition that is associated with an increased risk of developing diabetes. It has values a 0 or 1 where 0 indicates they don’t have heart disease and for 1 it means they have heart disease.
- smoking_history: Smoking history is also considered a risk factor for diabetes and can exacerbate the complications associated with diabetes.In our dataset we have 5 categories i.e not current,former,No Info,current,never and ever.
- bmi: BMI (Body Mass Index) is a measure of body fat based on weight and height. Higher BMI values are linked to a higher risk of diabetes. The range of BMI in the dataset is from 10.16 to 71.55. BMI less than 18.5 is underweight, 18.5-24.9 is normal, 25-29.9 is overweight, and 30 or more is obese.
- HbA1c_level: HbA1c (Hemoglobin A1c) level is a measure of a person's average blood sugar level over the past 2-3 months. Higher levels indicate a greater risk of developing diabetes. Mostly more than 6.5% of HbA1c Level indicates diabetes.
- blood_glucose_level: Blood glucose level refers to the amount of glucose in the bloodstream at a given time. High blood glucose levels are a key indicator of diabetes.
- diabetes:Diabetes is the target variable being predicted, with values of 1 indicating the presence of diabetes and 0 indicating the absence of diabetes.

### Problem Statement

Diabetes is a chronic disease that affects millions of people worldwide and is associated with significant health risks, including heart disease, kidney failure, and blindness. Early detection and preventive measures can substantially reduce the burden of the disease. However, identifying patients at risk for diabetes based on their medical and demographic data remains a challenge in healthcare. The goal of this analysis is to build predictive models that can accurately assess a patient’s risk of developing diabetes using features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. By leveraging machine learning techniques, we aim to provide healthcare professionals with a tool to assist in early identification of at-risk individuals, enabling timely interventions and personalized treatment plans.

### Business Context

The ability to predict diabetes at an early stage is essential for reducing healthcare costs and improving patient outcomes. Early identification of at-risk patients allows healthcare providers to intervene with preventive measures, including lifestyle modifications (e.g., diet, exercise) and early treatment plans, which can significantly delay or prevent the onset of diabetes.

For healthcare organizations and professionals, the ability to integrate predictive models into their workflow offers several benefits.
