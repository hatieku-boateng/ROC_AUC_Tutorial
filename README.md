# ROC Curves and AUC — A Deep Dive Tutorial

A beginner-friendly but technically detailed Jupyter notebook for understanding ROC curves and the AUC metric in machine learning.

## Overview

**Dataset:** Pima Indians Diabetes (768 samples, 8 features, binary outcome)  
**Models:** Logistic Regression · Random Forest · Gradient Boosting  
**Focus:** Deep conceptual understanding of ROC curves and AUC — not peak performance

## What You Will Learn

- What True Positive Rate, False Positive Rate, and Specificity mean — in words and formulas
- How classification thresholds work and what happens when you change them
- How to read and interpret an ROC curve (perfect, good, random, and bad curves)
- How to calculate and compare AUC scores across multiple models
- How to tune a threshold to optimise for a specific clinical or business goal
- Situations where ROC/AUC can be misleading

## Notebook Structure

| Section | Topic |
|---------|-------|
| Part 1 | Conceptual foundation — confusion matrix, TPR, FPR, Specificity |
| Part 2 | Classification thresholds — what they are and why they matter |
| Part 3 | ROC curves — construction, reading, interpretation |
| Part 4 | AUC — meaning, range, good vs bad values |
| Part 5 | Dataset loading and exploratory data analysis |
| Part 6 | Data preprocessing |
| Part 7 | Model training (3 models of increasing complexity) |
| Part 8 | Probability predictions and threshold demonstrations |
| Part 9 | ROC curves for all models on one plot |
| Part 10 | Threshold tuning — optimising TPR/FPR trade-off |
| Part 11 | Confusion matrices and full classification reports |
| Part 12 | Precision-Recall curves (bonus) |
| Part 13 | When ROC/AUC can be misleading |
| Part 14 | Summary and key takeaways |

## Requirements

```
numpy
pandas
scikit-learn
matplotlib
seaborn
```

Install dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

```bash
git clone https://github.com/hatieku-boateng/ROC_AUC_Tutorial.git
cd ROC_AUC_Tutorial
jupyter notebook "roc_auc_deep_dive copy.ipynb"
```
