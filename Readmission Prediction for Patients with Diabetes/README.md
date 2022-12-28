# Patients Readmission Prediction

## Overall Task:

Built machine learning models to predict if a patient with diabetes will be readmitted to the hospital within 30 days.

## Datasets: 
The data that is used in this project originally comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008). The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.
- It is an inpatient encounter (a hospital admission).
- It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
- The length of stay was at least 1 day and at most 14 days.
- Laboratory tests were performed during the encounter.
- Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.


## Table of Contents:

### [1. Initialization](https://github.com/91104311/Portfolio/blob/main/Readmission%20Prediction%20for%20Patients%20with%20Diabetes/Initialization%20-%20Patients%20Readmission%20Prediction.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 1.1. Import Libraries
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.2 Loading Data

### [2. Data Preprocessing](https://github.com/91104311/Portfolio/blob/main/Readmission%20Prediction%20for%20Patients%20with%20Diabetes/Data%20Preprocessing%20-%20Patients%20Readmission%20Prediction.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 2.1. Overview of the Dataset
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.2. Duplicate Records
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.3. Missing Values
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.4. Feature Engineering

### [3. Modeling]()

#### &nbsp;&nbsp;&nbsp;&nbsp; 3.1. Data Splitting and Scaling
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.2. Sampling
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.3. Model Selection
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.1. Naive Bayes
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.2. Logistic Regression
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.3. Stochastic Gradient Descent
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.4. Decision Tree
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.5. Random Forest 
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.6. Gradient Boosting Classifier
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.7. Ada Boost Classifier
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.4. Most Important Features Based on Random Forest
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.5. Model Comparison
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.5. Hyperparameter Tuning
