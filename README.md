# Diabetes-classification
Diabetes Classifier

## Introduction

Diabetes mellitus is a group of diseases that affects how the body regulates and uses glucose. It is characterized by abnormally high levels of glucose in the blood. A hormone known as insulin regulates glucose levels in the blood. It is produced by the islet cells in the pancreas—an impairment in the body's ability to make or respond to insulin results in diabetes. Diabetes is commonly classified into type 1 diabetes and type 2 diabetes. The former, also known as insulin-dependent diabetes, is an autoimmune disease whereby the islet cells are destroyed and unable to produce insulin, while the latter occurs when cells do not produce enough insulin and the body does not respond normally to insulin. Type 2 diabetes, also known as insulin-resistant diabetes, is the commonest type of diabetes. Other types include prediabetes and gestational diabetes. Using machine learning to diagnose diabetes will make the diagnostic process more efficient, which will, in turn, make treatment easier and perhaps more effective.

## Dataset Description

The dataset was downloaded from Kaggle and was originally obtained from the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) data repository. It contains several records of the Pima Indians of Arizona and Mexico. This population has the highest reported prevalence of diabetes of any group in the world. There are 8 Predictors in the dataset, which include the number of pregnancies the patient has had, their BMI, insulin level, age, blood pressure, diabetes pedigree function, and skin thickness

## Data Dictionary

Pregnancies: Number of times the patients have been pregnant
Glucose: Plasma glucose concentration in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skinfold thickness (mm)
Insulin: Two-hour serum insulin
BMI: Body Mass Index
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age in years
Outcome: Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0
## Objective

The aim is to build and compare several models that can accurately predict whether an individual has diabetes. The chosen classification algorithms include KNN, decision Tree, and different Naive Baiyes models. In this project, I performed the following steps:

- Exploratory data analysis
- Choosing a validation framework
- Comparing all the resulting models from the chosen algorithms
