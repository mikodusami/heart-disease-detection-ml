# Heart Disease Detection ML

A machine learning project for predicting heart disease risk using clinical and demographic features.

## Overview

This project develops and evaluates predictive models to identify patients at risk of heart disease. The workflow includes data preprocessing, exploratory data analysis, feature engineering, and model training with comprehensive performance evaluation.

## Dataset

The dataset contains clinical measurements and demographic information with a binary target variable indicating heart disease presence. Data is split into training (80%) and test (20%) sets.

### Key Files

- `data/heart_disease_cleaned.csv` - Cleaned dataset
- `data/X_train.csv`, `data/y_train.csv` - Training features and labels
- `data/X_test.csv`, `data/y_test.csv` - Test features and labels

## Project Workflow

### 1. Feature Understanding

**Notebook:** `feature-understanding.ipynb`

- Feature distributions and correlations
- Identifying key predictors
- Feature engineering insights

### 2. Data Cleaning & EDA

**Notebook:** `data-cleaning_eda_preprocessing.ipynb`

- Data quality assessment and cleaning
- Exploratory data analysis
- Statistical summaries and visualizations

### 3. Model Training & Evaluation

**Notebook:** `model-training-evaluation.ipynb`

- Model selection and training
- Hyperparameter tuning
- Cross-validation and performance metrics
- Results saved to `model_results.csv`

## Results

Model performance metrics and comparisons are documented in `model_results.csv`.

## Getting Started

### Requirements

- Python 3.x
- pandas, numpy, scikit-learn, matplotlib, seaborn
- Jupyter

### Running the Notebooks

```bash
jupyter notebook
```

Execute notebooks in order:

1. `feature-understanding.ipynb`
2. `data-cleaning_eda_preprocessing.ipynb`
3. `model-training-evaluation.ipynb`

## Project Structure

```
.
├── data/                              # Processed datasets
├── figures/                           # Generated visualizations
├── data-cleaning_eda_preprocessing.ipynb
├── feature-understanding.ipynb
├── model-training-evaluation.ipynb
├── model_results.csv
└── README.md
```
