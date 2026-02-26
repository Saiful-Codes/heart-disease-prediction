# Heart Disease Prediction

## Overview

This project presents a supervised machine learning pipeline for predicting the likelihood of heart disease using structured clinical data. The goal is to build and evaluate classification models that can assist in early risk identification based on patient health indicators.

The workflow includes data preprocessing, exploratory data analysis, feature preparation, model training, and performance evaluation using standard classification metrics.

---

## Problem Statement

Heart disease remains one of the leading causes of mortality worldwide. Early detection using patient health attributes can support preventive care and clinical decision-making.

This project aims to:

* Analyze key health features associated with heart disease
* Train and compare classification models
* Evaluate model performance using appropriate metrics
* Identify the most effective model for prediction

---

## Dataset

The dataset contains patient-level clinical features such as:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol
* Fasting blood sugar
* Maximum heart rate
* Exercise-induced angina
* ST depression and related cardiac indicators

The target variable indicates the presence or absence of heart disease.

---

## Methodology

### 1. Data Preprocessing

* Checked for missing values
* Performed data cleaning and formatting
* Separated features and target variable
* Train-test split for evaluation

### 2. Exploratory Data Analysis

* Statistical summaries
* Feature distribution analysis
* Correlation inspection

### 3. Model Training

Multiple classification models were trained and evaluated, including:

* Logistic Regression
* k-Nearest Neighbors
* Support Vector Machine
* Decision Tree
* Random Forest

### 4. Evaluation Metrics

Models were compared using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The best-performing model was selected based on overall predictive performance and generalization ability.

---

## Results

The final selected model achieved strong classification performance on the test set, demonstrating the effectiveness of classical supervised learning techniques for structured medical datasets.

Detailed evaluation metrics and comparisons are available in the notebook.

---

## Project Structure

```
heart-disease-prediction/
│
├── data/
├── notebooks/
│   └── heart_disease_model.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

Clone the repository:

```
git clone https://github.com/Saiful-Codes/heart-disease-prediction.git
cd heart-disease-prediction
```

Create and activate a virtual environment:

```
python -m venv .venv
.\.venv\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

Open the notebook:

```
jupyter notebook
```

---

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook
