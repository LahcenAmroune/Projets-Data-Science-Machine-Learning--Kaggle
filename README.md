# Data Science & Machine Learning Projects

A collection of hands-on data science projects covering the full workflow: data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling (classification and regression). Each project is self-contained, with its notebook/source code and the CSV dataset used.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## Table of Contents

- [Projects Overview](#projects-overview)
- [Project Details](#project-details)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)

---

## Projects Overview

| # | Project | Type | Goal |
|---|---------|------|------|
| 1 | [Analyzing Wildfire Activities in Australia](./Analyzing%20the%20wildfire%20activities%20in%20Australia) | EDA / Visualization | Explore wildfire patterns across Australian regions and time |
| 2 | [Building a Rainfall Prediction Classifier](./Building%20a%20Rainfall%20Prediction%20Classifier) | Classification | Predict whether it will rain from weather observations |
| 3 | [Data Analytics for House Pricing](./Data%20Analytics%20for%20House%20Pricing%20Data%20Set) | EDA / Regression | Identify the factors that drive house prices and model them |
| 4 | [Data Analytics for Insurance Cost](./Data%20Analytics%20for%20Insurance%20Cost%20Data%20Set) | EDA / Regression | Analyze and predict individual insurance costs |
| 5 | [Impact of Recession on Automobile Sales](./Impact%20of%20Recession%20on%20Automobile%20Sales) | EDA / Visualization | Study how economic recessions affect automobile sales |
| 6 | [Titanic Survival Prediction](./Titanic%20Survival%20Prediction) | Classification | Predict passenger survival from demographic and ticket data |

> Folder names in the links above must match your actual folder names exactly (spaces become `%20`).

---

## Project Details

### 1. Analyzing Wildfire Activities in Australia
- **Objective:** Understand how wildfire activity varies across Australian regions, seasons and years.
- **Data:** CSV file included in the project folder.
- **Approach:** Data loading and cleaning, aggregation by region and period, interactive and static visualizations.
- **Key findings:** <!-- TODO: add 2-3 concrete findings, e.g. which regions/months are most affected -->
- **Tools:** Python, Pandas, Matplotlib, Seaborn, Folium

### 2. Building a Rainfall Prediction Classifier
- **Objective:** Predict the presence or absence of rain from daily weather observations.
- **Data:** Large weather dataset (140,000+ observations), CSV included.
- **Approach:** Data cleaning, missing-value handling, categorical encoding (One-Hot), feature engineering, scikit-learn pipeline, hyperparameter tuning, evaluation with metrics suited to binary classification.
- **Results:** <!-- TODO: accuracy, plus precision / recall / F1 for BOTH classes, and the baseline accuracy of always predicting "no rain" -->
- **Tools:** Python, Pandas, Scikit-learn

### 3. Data Analytics for House Pricing
- **Objective:** Identify which features (size, location, condition, etc.) most influence house prices.
- **Approach:** EDA, correlation analysis, outlier inspection, regression modeling.
- **Results:** <!-- TODO: best model and its R² / RMSE -->
- **Tools:** Python, Pandas, NumPy, Seaborn, Scikit-learn

### 4. Data Analytics for Insurance Cost
- **Objective:** Analyze the factors behind insurance charges (age, BMI, smoking status, region, etc.) and predict costs.
- **Approach:** Data wrangling, EDA, feature encoding, regression modeling and evaluation.
- **Results:** <!-- TODO: best model and its R² / RMSE -->
- **Tools:** Python, Pandas, Seaborn, Scikit-learn

### 5. Impact of Recession on Automobile Sales
- **Objective:** Measure and visualize how recession periods affect automobile sales over time.
- **Approach:** Time-based analysis, comparison of recession vs. non-recession periods, visual storytelling with multiple chart types.
- **Key findings:** <!-- TODO: add 2-3 concrete findings -->
- **Tools:** Python, Pandas, Matplotlib, Seaborn

### 6. Titanic Survival Prediction
- **Objective:** Predict whether a passenger survived using demographic and ticket information.
- **Approach:** Missing-value imputation, feature engineering, model comparison, evaluation.
- **Results:** <!-- TODO: best model and its accuracy (state whether on validation or test data) -->
- **Tools:** Python, Pandas, Scikit-learn

---

## Repository Structure

```
.
├── Analyzing the wildfire activities in Australia/
├── Building a Rainfall Prediction Classifier/
├── Data Analytics for House Pricing Data Set/
├── Data Analytics for Insurance Cost Data Set/
├── Impact of Recession on Automobile Sales/
├── Titanic Survival Prediction/
└── README.md
```

Each project folder contains its source code (notebook or script) and the CSV dataset it uses.

---

## Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/LahcenAmroune/Projets-Data-Science-Machine-Learning--Kaggle.git
# 2. (Optional) create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn folium jupyter

# 4. Launch Jupyter and open a project's notebook
jupyter notebook
```

Datasets are stored locally in each project folder, so notebooks run without extra downloads.

---

## Tech Stack

- **Language:** Python
- **Data handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Folium
- **Machine learning:** Scikit-learn (pipelines, GridSearchCV, classification and regression models)
- **Environment:** Jupyter Notebook, Git/GitHub

---

## Skills Demonstrated

- Data cleaning and preprocessing (missing values, encoding, outliers)
- Exploratory data analysis and data storytelling
- Feature engineering and ML pipelines
- Classification and regression modeling
- Hyperparameter tuning and model evaluation
- Clear, reproducible project organization

---
## Contact

**Lahcen AMROUNE**
[LinkedIn](www.linkedin.com/in/lahcen-mokhtar-amroune) · [Email](mailto:amrounelahce91@gmail.com) 
