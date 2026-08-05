# 🏎️ The Economics of Winning: Predicting Formula One Team Revenue and Championship Success

A Statistics & Machine Learning project developed as part of the Master's programme at **SRH University of Applied Sciences Heidelberg**.

This project investigates the relationship between financial investment and competitive success in Formula One using historical financial and racing data. Machine learning techniques are applied to predict team revenue (regression) and the Constructors' Champion (classification).

---

# Project Objectives

The project addresses two supervised machine learning tasks:

### Regression
Predict Formula One team revenue using financial and performance indicators.

### Classification
Predict whether a team becomes the Constructors' Champion.

The project follows the complete machine learning workflow from data preparation to model evaluation and interpretation.

---

# Repository Structure

```
Final-Project-Examination/
│
├── Data_Selection_Preprocessing.ipynb
├── Statistical_Analysis_Visualization.ipynb
├── Feature Engineering and Feature Selection.ipynb
├── Revenue_Predictive_Modeling.ipynb
├── Championship_Classification_Modelling.ipynb
│
├── data/
│   ├── regression_dataset.csv
│   └── classification_dataset.csv
│
├── kagglehub/
│   └── datasets/
│       └── formula-1-racing-industry-2010-2026/
│           ├── constructor_finances.csv
│           ├── f1_business.csv
│           ├── race_results.csv
│           ├── circuit_economics.csv
│           └── driver_standings.csv
│
├── Presentation-and-Report/
│   ├── F1 Economics of Winning Report.pdf
│   └── F1_Project_Presentation.pdf
│
├── predicted_2027_revenue.csv
├── 2027_revenue_forecast.png
├── model_comparison.png
├── classification_roc_pr_curves.png
├── classification_confusion_matrices.png
└── residual_analysis.png
```

---

# Machine Learning Workflow

The notebooks are intended to be executed in the following order:

### 1. Data Selection & Preprocessing

Notebook:

```
Data_Selection_Preprocessing.ipynb
```

Tasks performed:

- Load Formula One datasets
- Merge relational tables
- Handle missing values
- Outlier analysis
- One-hot encoding
- StandardScaler
- Data leakage prevention
- Train-test split
- Export regression and classification datasets

---

### 2. Statistical Analysis & Visualization

Notebook:

```
Statistical_Analysis_Visualization.ipynb
```

Includes:

- Descriptive statistics
- Histograms
- Scatter plots
- Heatmaps
- Boxplots
- Violin plots
- Correlation analysis
- Statistical hypothesis testing

---

### 3. Feature Engineering & Feature Selection

Notebook:

```
Feature Engineering and Feature Selection.ipynb
```

Tasks:

- Create engineered features
- Correlation analysis
- Mutual Information
- ANOVA
- Random Forest Feature Importance
- Final feature selection

---

### 4. Revenue Prediction

Notebook:

```
Revenue_Predictive_Modeling.ipynb
```

Models evaluated:

- Naive Baseline
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor

Evaluation metrics:

- R²
- RMSE

Outputs:

- Revenue forecasts
- Residual analysis
- Model comparison
- 2027 revenue prediction

---

### 5. Championship Prediction

Notebook:

```
Championship_Classification_Modelling.ipynb
```

Models evaluated:

- Logistic Regression
- Random Forest
- Naive Baseline

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

Outputs:

- Confusion matrices
- ROC Curve
- Precision-Recall Curve

---

# Installation

## Clone the repository

```bash
git clone https://github.com/<username>/<repository>.git
```

Move into the project folder

```bash
cd Final-Project-Examination
```

---

## Create a virtual environment

### Windows

```bash
python -m venv .venv
```

Activate

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

## Install dependencies

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is not included, install the required packages manually:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter kagglehub
```

---

# Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Execute the notebooks in the following order:

1. Data_Selection_Preprocessing.ipynb
2. Statistical_Analysis_Visualization.ipynb
3. Feature Engineering and Feature Selection.ipynb
4. Revenue_Predictive_Modeling.ipynb
5. Championship_Classification_Modelling.ipynb

Each notebook depends on the outputs produced by the previous stages.

---

# Dataset

Dataset Source:

**Formula 1 Racing Industry Dataset (2010–2026)**

Contains information on:

- Team finances
- Business metrics
- Race results
- Driver standings
- Circuit economics

These datasets are merged into analytical datasets used for regression and classification.

---

# Results

The project demonstrates that:

- Operating Budget is the strongest predictor of team revenue.
- Financial investment strongly correlates with competitive success.
- Lasso Regression achieved the best revenue prediction performance.
- Logistic Regression produced strong championship prediction performance.
- Machine learning effectively models both the business and sporting aspects of Formula One.

---

# Generated Outputs

The project generates several outputs, including:

- Predicted 2027 team revenue
- Revenue forecast visualizations
- Model comparison plots
- Residual analysis
- ROC Curve
- Precision-Recall Curve
- Confusion Matrices

---

# Authors

- Suryawanshi Sahil Chandrakant
- Wadile Hrithik Ramesh,
- Myakal Akshay Pramod, 
- Kenkere Sridhar Shashank,
- Boafo Frederick​

---

# License

This repository was developed for academic purposes as part of the Statistics & Machine Learning course at SRH University of Applied Sciences Heidelberg.