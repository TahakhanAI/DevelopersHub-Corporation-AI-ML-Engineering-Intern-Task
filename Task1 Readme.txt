# Iris Dataset Exploration and Visualization

## Objective
This project focuses on exploring and visualizing the Iris dataset using Python libraries such as pandas, matplotlib, and seaborn. The goal is to understand the structure of the dataset, analyze statistical summaries, and identify patterns through visualizations.

---

## Dataset
The Iris dataset contains measurements of iris flowers from three different species:
- Setosa
- Versicolor
- Virginica

Features included:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

The dataset can be loaded directly using seaborn.

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## Steps Performed

### 1. Data Loading
- Loaded the Iris dataset using seaborn/pandas.
- Converted it into a pandas DataFrame.

### 2. Data Inspection
Performed:
- `.shape`
- `.columns`
- `.head()`
- `.info()`
- `.describe()`

These methods helped understand:
- Dataset size
- Data types
- Missing values
- Statistical summaries

### 3. Data Visualization

#### Scatter Plot
Used scatter plots to visualize relationships between:
- Sepal Length vs Petal Length
- Sepal Width vs Petal Width

Species were differentiated using colors.

#### Histograms
Histograms were used to understand:
- Feature distributions
- Frequency patterns
- Data spread

#### Box Plots
Box plots helped identify:
- Outliers
- Median values
- Interquartile ranges

---

## Skills Demonstrated
- Data loading and preprocessing using pandas
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Data visualization using matplotlib and seaborn

---

## Example Libraries Import

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt