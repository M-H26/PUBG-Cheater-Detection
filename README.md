# PUBG Cheater Detection

A Machine Learning course project that aims to identify potentially cheating PUBG players by analyzing gameplay behavior and match statistics.

## Project Overview

The project is framed as a **binary classification** problem:

- **Input:** Player or match-level gameplay statistics and behavioral features.
- **Output:** A predicted class indicating whether the player is legitimate or cheating.
  - `0` — Legitimate Player
  - `1` — Cheater

The project idea is based on the *PUBG Cheater Detection* proposal in the Machine Learning Project Ideas document.

## Objectives

- Explore and understand the selected dataset.
- Clean and prepare the data for machine learning.
- Investigate the target distribution and address class imbalance if needed.
- Encode categorical features and scale numerical features where appropriate.
- Train and compare the classification models covered in the course.
- Tune model hyperparameters using `GridSearchCV`.
- Evaluate models using suitable classification metrics.
- Select the best-performing model and justify the choice.

## Dataset

**Dataset:** To be selected / confirmed.

The dataset source, size, feature descriptions, target definition, and license will be documented here after the team finalizes the dataset.

## Project Workflow

1. Dataset selection and understanding
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Feature preparation
5. Classification model training
6. Model comparison and selection
7. Hyperparameter tuning with `GridSearchCV`
8. Final evaluation and conclusions

## Models

Models will be added here as the team confirms the full list of classification algorithms covered in the course.

### Models covered so far

- Naive Bayes
- Decision Tree

**Course-scope note:** Gradient Descent for Simple Linear Regression and Multiple Linear Regression have also been covered, but these are regression methods and are not directly applicable to the current binary classification target.

## Evaluation Metrics

The project requirements specify the following classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Repository Structure

```text
PUBG-Cheater-Detection/
├── README.md
├── .gitignore
└── notebooks/
    └── EDA.ipynb
```

Additional notebooks and folders will be added after the team agrees on the project workflow and task distribution.

## Team

Team members and individual responsibilities will be added after they are finalized.

## Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Project Status

**Initial setup — dataset selection and detailed workflow are still to be finalized.**

## Author

**Mohamed Hany**

Computer Science – Data Science

Orange Digital Hub – Data Analysis & AI Training

GitHub: [M-H26](https://github.com/M-H26)

LinkedIn: [Mohamed Hany](https://www.linkedin.com/in/mohamed-hamouda06/)
