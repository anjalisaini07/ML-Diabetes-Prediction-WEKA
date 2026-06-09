
# Diabetes Prediction Using Machine Learning in WEKA

A machine learning project focused on predicting diabetes outcomes using the Pima Indians Diabetes Dataset and the WEKA data mining platform. This project demonstrates data preprocessing, supervised classification, model comparison, feature importance analysis, and decision tree visualization using multiple machine learning algorithms.

---

## Project Overview

This project applies machine learning techniques to classify diabetic and non-diabetic patients based on clinical attributes such as Glucose, BMI, Age, Blood Pressure, and Insulin levels. The workflow was implemented entirely in WEKA using its graphical interface and built-in machine learning tools.

The project includes:

* Data preprocessing and missing value handling
* Classification using multiple ML algorithms
* 10-fold cross-validation
* Performance comparison
* Decision tree visualization
* Feature importance analysis

---

## Dataset

**Dataset:** Pima Indians Diabetes Dataset
**Instances:** 768 patient records
**Attributes:** 8 clinical features + 1 outcome class

### Features

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome (0 = Non-diabetic, 1 = Diabetic)

---

## Tools & Technologies

* WEKA
* J48 Decision Tree
* Random Forest
* Naive Bayes
* Logistic Regression
* SMO (Support Vector Machine)
* IBk (k-NN)

---

## Workflow

1. Load dataset into WEKA
2. Handle missing values using ReplaceMissingValues filter
3. Convert class attribute to nominal
4. Apply machine learning classifiers
5. Perform 10-fold cross-validation
6. Compare model performance
7. Analyze feature importance
8. Visualize decision tree results

---

## Machine Learning Models Evaluated

| Model               | Accuracy |
| ------------------- | -------- |
| SMO (SVM)           | 77.34%   |
| Logistic Regression | 77.21%   |
| Naive Bayes         | 76.30%   |
| Random Forest       | 75.26%   |
| IBk (k-NN)          | 70.18%   |

### Best Performing Model

SMO (Support Vector Machine) achieved the highest classification accuracy of **77.34%**.

---

## Key Findings

* Glucose level was identified as the most important predictor of diabetes risk.
* BMI and Age also showed strong influence on classification outcomes.
* J48 provided an interpretable decision tree for clinical understanding.
* Cross-validation demonstrated stable model performance across classifiers.


---

## Applications

* Biomedical data analysis
* Clinical decision support
* Disease risk prediction
* Healthcare machine learning education
* Bioinformatics and medical AI learning

---

## Author

Anjali saini
M.Sc. Bioinformatics
Maharshi Dayanand University, Rohtak
