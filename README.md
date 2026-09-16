# Machine Learning Capstone Project

This repository contains a comprehensive Machine Learning Capstone Project divided into two distinct tracks: a **Classification Track** and a **Regression Track**. Each track demonstrates the end-to-end machine learning lifecycle, starting from data ingestion and Exploratory Data Analysis (EDA) to feature engineering, model development, hyperparameter tuning, and comprehensive model evaluation.

## Project Structure

```text
├── notebooks/
│   ├── classification.ipynb  # Classification track notebook
│   └── regression.ipynb      # Regression track notebook
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation (this file)
```

## Track 1: Classification
**Notebook:** [`notebooks/classification.ipynb`](notebooks/classification.ipynb)  
**Dataset:** CIC-MalMem-2022

This track focuses on a classification problem utilizing the CIC-MalMem-2022 dataset to identify malicious memory events. The notebook includes:
- **Exploratory Data Analysis (EDA):** Target distribution analysis, feature distribution visualizations, correlation heatmaps, and feature-target relationships.
- **Preprocessing & Feature Engineering:** Data cleaning, handling missing/duplicate values, encoding categorical variables, scaling numerical features, and splitting the dataset.
- **Model Development & Evaluation:** Implementing classification algorithms, predicting outcomes, and evaluating performance using confusion matrices and metric comparison tables.

## Track 2: Regression
**Notebook:** [`notebooks/regression.ipynb`](notebooks/regression.ipynb)  
**Dataset:** Superconductivity Dataset (Predicting Superconducting Critical Temperature)

This track is dedicated to predicting the superconducting critical temperature using various regression techniques. The notebook encompasses:
- **Extensive EDA:** Detailed audit of dataset dimensions, missing values, duplicates, and statistical summaries. It features univariate distribution analysis, correlation checks, and feature-target relationships.
- **Data Preprocessing & Feature Engineering:** Addressing constant/near-constant features, outlier detection, data scaling, and engineered transformations.
- **Model Development:** Evaluation of multiple regression algorithms, including:
  - Linear, Ridge, Lasso, and ElasticNet Regression
  - Polynomial Regression
  - Decision Tree, Random Forest, and Gradient Boosting Regressors
  - Support Vector Regression (SVR)
  - K-Nearest Neighbors (KNN) Regressor
- **Hyperparameter Tuning & Selection:** Fine-tuning parameters for top models (like Random Forest and KNN regressors), selecting the best-performing models, analyzing prediction residuals, and determining feature importances.
- **Advanced Analysis:** Five-fold cross-validation of the best models, Lasso regression sparsity analysis, and polynomial regression degree comparisons.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SharveshC/ML_CAPSTONE.git
   cd ML_CAPSTONE
   ```

2. **Install dependencies:**
   Ensure you have Python installed, then install the required packages using `pip`:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks:**
   Launch Jupyter Notebook to interact with the notebooks:
   ```bash
   jupyter notebook
   ```
   Open `notebooks/classification.ipynb` or `notebooks/regression.ipynb` from the Jupyter interface.

## Requirements

The project relies on the following key Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

For a complete list of dependencies, see [`requirements.txt`](requirements.txt).
