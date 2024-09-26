# Breast-Cancer-Classification-using-PCA-and-Logistic-Regression
This project implements a classification model for breast cancer diagnosis using Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for prediction. The dataset used is the Breast Cancer Wisconsin dataset from sklearn.datasets.

# Features:
- Data Loading: The dataset was loaded, containing features related to various characteristics of cell nuclei present in breast cancer biopsies.
- Data Preprocessing:
Applied StandardScaler for feature scaling to standardize the dataset.
- Dimensionality Reduction:
Implemented PCA to reduce the dimensionality of the dataset to two principal components, facilitating easier visualization and analysis.
- Model Training:
The dataset was split into training and testing sets (80-20 split).
Trained a Logistic Regression model on the principal components.
- Visualization:
A scatter plot visualizing the first two principal components colored by the target variable (cancer diagnosis: malignant or benign).

# Requirements:
- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, scikit-learn
