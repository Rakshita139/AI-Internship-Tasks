# AI Internship Tasks

## Overview

This repository contains the completed tasks for my Artificial Intelligence Internship. The projects demonstrate practical knowledge of machine learning, model deployment, and responsible AI using Python.

---

## Student Information

**Intern:** Rakshita

**Domain:** Artificial Intelligence

---

# Task 1 – ML Classification Project

## Objective

Build and evaluate a supervised machine learning classification model using the Titanic dataset.

## Dataset

Titanic Survival Dataset

Target Variable:
- Survived

## Algorithms Used

- Logistic Regression
- Random Forest Classifier

## Preprocessing

- Loaded dataset using Pandas
- Handled missing values
- Encoded categorical columns
- Removed unnecessary columns
- Split dataset into training and testing sets

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

# Task 3 – Model Deployment

## Objective

Deploy the trained machine learning model using FastAPI.

## Files

- app.py
- titanic_model.pkl

## Features

- Loads trained Random Forest model
- Predicts Titanic survival
- FastAPI REST API
- Tested locally using Uvicorn

---

# Task 4 – Responsible AI & Model Interpretation

## Objective

Interpret the machine learning model and understand feature importance.

## Techniques Used

- Random Forest Feature Importance
- Bias Analysis
- Fairness Considerations
- Explainability

## Results

Feature importance graph generated successfully.

---

# Technologies Used

- Python 3.14
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- FastAPI
- Uvicorn
- Joblib

---

# Environment Setup

## Install Python

Download and install Python from:

https://www.python.org/downloads/

---

## Install Required Libraries

Open Command Prompt or PowerShell and run:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter fastapi uvicorn joblib python-multipart
```

---

## Start Jupyter Notebook

```bash
jupyter notebook
```

Open the required notebook and run all cells.

---

# Running Task 3 API

Open Command Prompt or PowerShell.

Navigate to the deployment folder.

Example:

```bash
cd Task3_Deployment
```

Run the API:

```bash
uvicorn app:app --reload
```

Server starts at:

```
http://127.0.0.1:8000
```

Swagger Documentation:

```
http://127.0.0.1:8000/docs
```

---

# Repository Contents

```
Task1_ML_Classification.ipynb

Task1_Report.pdf

Task3_Model_Deployment.ipynb

Task3_Model_Deployment_Report.pdf

Task4_Responsible_AI.ipynb

Task4_Responsible_AI_Report.pdf

app.py

titanic_model.pkl

README.md
```

---

# Project Outcome

Successfully completed:

- Machine Learning Classification
- Model Evaluation
- FastAPI Model Deployment
- Responsible AI Analysis
- Model Interpretation

---

# Conclusion

This internship project provided practical experience in:

- Data preprocessing
- Machine learning model development
- Model evaluation
- Model deployment using FastAPI
- Responsible AI concepts
- Model interpretation and explainability

The projects helped strengthen practical AI and Python programming skills.


## Author

Rakshita

Artificial Intelligence Internship
