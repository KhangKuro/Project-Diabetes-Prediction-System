<img src="https://github.com/KhangKuro/Project-Diabetes-Prediction-System/blob/main/picture.png" />

# Diabetes Prediction System - Predicting Diabetes

## Purpose

This project aims to build a diabetes prediction system based on diagnostic parameters and a dataset collected from Kaggle. Using data analysis and modeling techniques, we have performed a series of steps to process the data and construct a prediction model.

## Content

### 1. Load the Dataset

Dataset source: [Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

### 2. Exploratory Data Analysis

This dataset is obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. The goal is to predict based on diagnostic measures whether a patient has diabetes or not. All patients are females aged 21 and above in India.

There are a total of 9 columns corresponding to 9 variables as follows:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

The dataset has no missing values. However, data preprocessing is required to replace values with 0.

### 3. Data Visualization

#### 3.1 Boxplot

The boxplot illustrates the distributional position of each variable in the dataset.

#### 3.2 Column and Estimated Curve Charts

The estimated curve of each variable represents its distribution.

### 4. Data Pre-processing

#### 4.1 Handling Missing Values

Replacement of values with 0 in the dataset is necessary.

#### 4.2 Addressing Data Imbalance

Addressing data imbalance during the Machine Learning model building process.

### 5. Model Building

#### 5.1 Data Splitting and Model Comparison

Utilizing different algorithms and comparing their performance.

#### 5.2 Model Selection

Using Decision Tree with the highest performance.

### 6. Review

#### 6.1 Classification Report

Evaluation of the prediction model's results.

#### 6.2 Confusion Matrix

Displaying the model's prediction results on the confusion matrix.

---

Thank you for reading. Feel free to contribute opinions or add information to the project!
Special thanks to LinhChiHo for their invaluable guidance and insights throughout the development of this project!
