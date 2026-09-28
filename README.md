
# Predicting Defect Rates in Manufacturing Using Machine Learning

## Author
**Gokul Kailash**

## Overview

This project focuses on predicting defect rates in manufacturing using Machine Learning and Data Science techniques. It explores how feature engineering, feature selection, and model tuning influence the predictive performance of regression models.

The project uses a synthetic manufacturing dataset sourced from Kaggle and includes Jupyter notebooks covering data analysis, feature engineering, model development, and evaluation.

## Problem Statement

Manufacturing defects can affect product quality, production efficiency, and operational costs. Predicting defect rates using machine learning can help identify patterns in manufacturing data and support quality analysis.

The objective of this project is to analyze manufacturing data and evaluate machine learning models for predicting defect rates.

## Objectives

- Perform Exploratory Data Analysis (EDA).
- Apply feature engineering techniques.
- Split data into training and testing datasets.
- Analyze the impact of engineered features on model performance.
- Train and evaluate regression models.
- Perform feature selection and hyperparameter tuning.
- Analyze feature importance and prediction errors.

## Dataset

**Dataset Name:** Predicting Manufacturing Defects Dataset  
**File Name:** `manufacturing_defect_dataset.csv`  
**Source:** Kaggle  
**Dataset Creator:** Rabie El Kharoua

Dataset Link:  
https://www.kaggle.com/datasets/rabieelkharoua/predicting-manufacturing-defects-dataset/data

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- LightGBM
- Jupyter Notebook

## Project Structure

```text
Predicting-Defect-Rates-in-Manufacturing/
│
├── README.md
├── LICENSE
├── manufacturing_defect_dataset.csv
│
└── notebooks/
    ├── 01_eda.ipynb
    ├── 02_feature_engineering.ipynb
    ├── 03_splitting_data.ipynb
    ├── 04_rq2_feature_engineering_impact.ipynb
    └── 05_modeling_pipeline.ipynb
```

## Project Workflow

### 1. Exploratory Data Analysis
Analyze the dataset, understand variable distributions, and identify patterns in manufacturing defect rates.

### 2. Feature Engineering
Create additional features from existing data to investigate whether they improve model performance.

### 3. Data Splitting
Divide the dataset into training and testing sets for model development and evaluation.

### 4. Feature Engineering Impact Analysis
Evaluate how additional engineered features affect the predictive performance of regression models.

### 5. Model Development and Evaluation
Perform feature selection, model training, hyperparameter tuning, feature importance analysis, model evaluation, and error analysis.

## Installation

### Step 1: Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### Step 2: Navigate to the Project Directory

```bash
cd Predicting-Defect-Rates-in-Manufacturing-Using-Machine-Learning
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn lightgbm jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the `notebooks/` directory and execute the cells in sequence.

## Expected Outcomes

- Understand patterns in manufacturing defect data.
- Explore the impact of feature engineering on regression performance.
- Compare predictive model performance.
- Identify important features influencing predictions.
- Analyze model errors and prediction accuracy.

## Data Source and Acknowledgments

The dataset used in this project was created by **Rabie El Kharoua** and is hosted on Kaggle.

Dataset: https://www.kaggle.com/datasets/rabieelkharoua/predicting-manufacturing-defects-dataset/data

Parts of the code were generated with assistance from OpenAI's ChatGPT.

## License

This project is licensed under the MIT License. Refer to the `LICENSE` file for details.

## Author

**Gokul Kailash**
