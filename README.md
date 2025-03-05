# Solubility Prediction Machine Learning Project

## Overview
This project implements machine learning models to predict molecular solubility using the Delaney solubility dataset. Two regression algorithms are compared: Linear Regression and Random Forest.

## Data Source
Dataset: Delaney Solubility Descriptors
- Source URL: `https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv`
- Original Repository: [Data Professor GitHub](https://github.com/dataprofessor/data)

### Data Loading Code
```python
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv')
```

## Models Implemented
1. **Linear Regression**
   - Training MSE: 1.0075
   - Training R²: 0.7645
   - Testing MSE: 1.0207
   - Testing R²: 0.7892

2. **Random Forest**
   - Training MSE: 1.0282
   - Training R²: 0.7597
   - Testing MSE: 1.4077
   - Testing R²: 0.7092

## Key Learnings
- Data preprocessing
- Model training and evaluation
- Performance metrics interpretation
- Comparative analysis of machine learning algorithms

## Requirements
- Python 3.x
- scikit-learn
- pandas
- matplotlib

## How to Run
1. Clone the repository
2. Install required libraries
3. Run the Jupyter notebook
