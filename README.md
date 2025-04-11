EEG Brain Data Classification – GSoC Project

This project performs classification of brain EEG signals to identify neural/metabolic states using traditional ML models. It includes data analysis, model training, evaluation, and feature selection.


The dataset contains 64-channel EEG recordings with band power features in theta, delta, alpha, beta, and gamma ranges. Two output classes are provided.

[Link to dataset](https://docs.google.com/spreadsheets/d/e/2PACX-1vSC87hYugbdg0_MbAhqVHaGSTk_-tEb_X_1YeXo6qzuz-bKm3Vo3gQd6m4IlZ5CAQMUUxfZrtCgbWYv/pub?output=csv)

ML Models Used:

- Logistic Regression
- Support Vector Machine (Linear + RBF)
- k-Nearest Neighbors (kNN)

Feature Selection:

- Univariate Feature Selection (UFS)
- Recursive Feature Elimination (RFE)
- Principal Component Analysis (PCA)

Evaluation Metrics:

- Accuracy
- Precision
- Confusion Matrix

Tools & Libraries:

- Python (Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn)
- Google Colab
