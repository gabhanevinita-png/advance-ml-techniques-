# Advanced Machine Learning Techniques

A hands-on machine learning project exploring ensemble learning algorithms, feature selection, imbalanced dataset handling, and Explainable AI (XAI) using Python.

## Project Overview

This project demonstrates the implementation and comparison of three ensemble learning algorithms:

- Random Forest
- Gradient Boosting
- XGBoost

It also explores techniques such as Feature Importance, Feature Selection, SMOTE, and SHAP to understand model performance and interpretability.

The project uses the Breast Cancer Wisconsin dataset available in Scikit-learn.

## Objectives

- Understand ensemble learning techniques.
- Compare different machine learning algorithms.
- Identify the most important features in a dataset.
- Reduce unnecessary features through feature selection.
- Handle class imbalance using SMOTE.
- Interpret machine learning predictions using SHAP.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical operations |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Scikit-learn | Machine learning algorithms |
| XGBoost | Gradient boosting |
| Imbalanced-learn | SMOTE implementation |
| SHAP | Model explainability |
| Google Colab | Development environment |

## Dataset

**Breast Cancer Wisconsin Dataset**

- Source: Scikit-learn
- Total records: 569
- Features: 30
- Target classes: Malignant and Benign
- Problem type: Binary Classification

## Machine Learning Algorithms

### 1. Random Forest
An ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

### 2. Gradient Boosting
A boosting algorithm that builds decision trees sequentially, with each new tree attempting to correct previous errors.

### 3. XGBoost
An optimized gradient boosting algorithm designed for efficient and accurate model training.

## Techniques Implemented

### Feature Importance
Identifies the input features that contribute most to model predictions.

### Feature Selection
Selects the top 10 features based on Random Forest feature importance and evaluates a model using the selected features.

### SMOTE
Synthetic Minority Over-sampling Technique generates synthetic minority-class samples to address class imbalance.

SMOTE is applied only to the training dataset to avoid data leakage.

### SHAP Explainability
SHAP (SHapley Additive exPlanations) explains how individual features contribute to model predictions.

It provides insights into both global feature importance and individual predictions.

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Split data into training and testing sets.
4. Train Random Forest, Gradient Boosting and XGBoost models.
5. Compare model performance.
6. Calculate feature importance.
7. Perform feature selection.
8. Apply SMOTE to training data.
9. Evaluate the model.
10. Generate SHAP explanations.

## Results and Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

The project also compares feature importance and explores how SMOTE and feature selection affect model performance.

Actual model scores should be taken from the executed notebook.

## Repository Structure

```text
Advanced-Machine-Learning-Techniques/
│
├── Day1_Advanced_ML.ipynb
├── README.md
└── images/
    ├── model_comparison.png
    ├── feature_importance.png
    └── shap_summary.png
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/Advanced-Machine-Learning-Techniques.git
```

2. Install the dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn xgboost imbalanced-learn shap
```

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Run the notebook cells sequentially.

## Learning Outcomes

Through this project, I gained practical experience in:

- Ensemble learning algorithms.
- Model comparison and evaluation.
- Feature selection and importance.
- Handling imbalanced datasets.
- Explainable Artificial Intelligence.

## Author

**Vignesh Gabhane**

Computer Science Engineering – Artificial Intelligence and Machine Learning

GitHub: https://github.com/gabhanevinita-png

LinkedIn: https://www.linkedin.com/in/vignesh-gabhane-8a521b3a/
