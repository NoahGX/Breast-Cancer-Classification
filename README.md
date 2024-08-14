# Breast Cancer Classification using Principal Component Analysis (PCA) and Support Vector Machines (SVM)

## Overview
The purpose of this Jupyter Notebookis to apply Principal Component Analysis (PCA) and Support Vector Machine (SVM) techniques to classify instances of breast cancer as benign or malignant based on features from the breast cancer dataset. The notebook demonstrates the power of dimensionality reduction with PCA and the effectiveness of SVM in classification tasks.

## Features
- **Data Loading**: Loads and examines the breast cancer dataset.
- **Data Normalization**: Standardizes the dataset to have a mean of zero and a variance of one.
- **PCA Application**: Reduces the dimensionality of the data while retaining 90% of the variance.
- **Variance Analysis**: Visualizes the cumulative variance explained by the components.
- **SVM Classification**: Implements SVM to classify the data into benign or malignant categories.
- **Visualization**: Plots decision boundaries using PCA-reduced data.

## Usage
- Open the notebook in a Jupyter environment.
- Run each cell in order from top to bottom.
- Adjust the PCA variance threshold or SVM parameters as needed for different analysis.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `NumPy`, `Pandas`, `scikit-learn`, `Plotly`, and `Matplotlib`.

## Input
The notebook utilizes the breast cancer dataset from `sklearn.datasets`.

## Output
- A line plot of the cumulative variance explained by the PCA components.
- A classification report detailing accuracy, precision, recall, and F1-score of the SVM model.
- Scatter plots and contour plots visualizing the SVM decision boundaries.

## Notes
- Ensure all dependencies are installed before running the notebook.
- Adjustments in PCA components or SVM parameters may be needed based on specific requirements or updates in the dataset.