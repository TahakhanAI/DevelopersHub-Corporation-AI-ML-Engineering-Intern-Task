
---

# Task 3 — README.md

```md
# Heart Disease Prediction Using Machine Learning

## Objective
The purpose of this project is to predict whether a person is at risk of heart disease using medical and health-related attributes.

---

## Dataset
This project uses the Heart Disease UCI Dataset available on Kaggle.

The dataset includes features such as:
- Age
- Sex
- Chest Pain Type
- Cholesterol
- Blood Pressure
- Maximum Heart Rate
- Fasting Blood Sugar
- ECG Results

Target Variable:
- Presence or absence of heart disease

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## Project Workflow

### 1. Data Loading
Loaded the dataset using pandas.

```python
import pandas as pd

df = pd.read_csv("heart.csv")