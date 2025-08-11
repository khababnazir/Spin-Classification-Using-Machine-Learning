# Spin Classification Using Machine Learning

This repository contains the Python code and implementation for a project exploring the application of various machine learning algorithms to the fundamental physics problem of classifying quantum spin states.
For detailed analysis please read the report

## Project Overview

The core objective of this project is to distinguish between **spin-up** and **spin-down** particles based on simulated data from a Stern-Gerlach-like experiment. This is framed as a supervised binary classification task. The classification is performed using two simulated physical observables:

*   **Positional Deflection:** The final position of a particle after passing through an inhomogeneous magnetic field.
*   **Interaction Energy:** A secondary energy measurement associated with the particle's state.

A comprehensive comparison of five different classification models was conducted to evaluate their performance on this task:

1.  **Boosted Decision Tree (BDT)**
2.  **Support Vector Machine (SVM)**
3.  **Logistic Regression**
4.  **K-Nearest Neighbors (KNN)**
5.  **Artificial Neural Network (ANN)**

## Detailed Project Report

This repository provides the complete code for the project in the `Spin Classification.ipynb` Jupyter Notebook.

**For a comprehensive discussion of the underlying physics, the mathematical formalism of the machine learning models, and a detailed interpretation of all results—including ROC curves, confusion matrices, learning curves, and feature importance—please refer to the full project report.**

The report contains the in-depth analysis and conclusions drawn from the experiments implemented in the notebook.

## How to Run the Code

To run the analysis yourself, you can open the `Spin Classification.ipynb` file in a Jupyter Notebook or JupyterLab environment.

### Required Libraries
The main Python libraries used in this project are:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow`

These can be installed via `pip` or `conda`
