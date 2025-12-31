# SVM Letter Recognition

This project implements letter recognition using Support Vector Machines (SVM). It explores linear, polynomial, and RBF kernels, evaluates their performance, and demonstrates how kernel selection impacts classification accuracy.

## Repository structure

- notebooks/
  - SVM_letter_recognition.ipynb — Jupyter notebook that contains data loading, preprocessing, model training, evaluation, visualizations, and result comparisons for different SVM kernels.
- data/

> Note: The repository primarily consists of a Jupyter Notebook; the instructions below assume you will run the notebook locally or in a cloud notebook environment.

## Dataset

The notebook uses a letter recognition dataset (commonly available as the Letter Recognition dataset from the UCI Machine Learning Repository or similar). The notebook includes steps to load and preprocess the dataset — scaling features, splitting into train/test sets, and converting labels as required.

## What this project demonstrates

- How to train SVM classifiers with different kernels: linear, polynomial, and RBF.
- How kernel choice affects model accuracy, decision boundaries, and generalization.
- Model evaluation using accuracy, confusion matrix, and classification reports.
- Visual comparisons of performance and (when feasible) 2D projections of decision boundaries.

## Requirements

Recommended Python packages (install with pip):

```bash
pip install -r requirements.txt
# or
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
