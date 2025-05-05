# Diabetes Prediction Project

This project applies predictive analytics and machine learning techniques to identify individuals at risk of developing diabetes based on health-related factors. By leveraging historical data, the goal is to create predictive models that can assist healthcare professionals in making informed decisions and prioritizing preventive care.

## Dataset

For this analysis, the **Pima Indians Diabetes Dataset** is used. This dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases and focuses on a population of Pima Indian women aged 21 years and older who are at least partially of Pima heritage and were living in Arizona. The dataset contains 768 records and 8 independent variables representing health measurements, along with one dependent variable indicating whether the individual has diabetes.

The variables included in the dataset are:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration (2-hour oral glucose tolerance test)
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function which scores likelihood of diabetes based on family history
- **Age**: Age in years
- **Outcome**: Class variable (0 = non-diabetic, 1 = diabetic)

This dataset is widely used in machine learning education and research as it represents a real-world medical prediction problem with measurable health indicators.

## Business Questions

1. What key patient characteristics are associated with a higher likelihood of having diabetes?
2. How accurately can we predict the likelihood of diabetes using patient health metrics?
3. Can predictive modeling assist healthcare providers in identifying high-risk individuals for early intervention?

## Project Objectives

- Identify the most important health-related predictors of diabetes among Pima Indian women.
- Develop and compare the performance of at least two predictive models for diabetes diagnosis.
- Generate insights that could support healthcare professionals in screening and preventive strategies.

## Models & Metrics

| Model               | Accuracy | F1 Score | AUC  |
|--------------------|----------|----------|------|
| Logistic Regression | 0.75     | 0.64     | 0.82 |
| Random Forest       | 0.74     | 0.64     | 0.83 |

## Instructions

See the notebook file for code, EDA, modeling, and analysis.

## References

- National Institute of Diabetes and Digestive and Kidney Diseases.  
- Dataset source: [https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?resource=download]
