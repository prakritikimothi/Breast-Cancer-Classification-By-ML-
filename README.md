# Breast-Cancer-Classification-By-ML-
This is a Breast Cancer Classification Prediction Model implemented using Logical Regression algorithm of Machine Learning
Breast Cancer Classification Prediction Model
Overview
This project implements a Breast Cancer Classification model using the Logistic Regression algorithm. The model is designed to classify breast cancer tumors as either malignant (0) or benign (1) based on the provided input features. The dataset used is the popular Breast Cancer Wisconsin (Diagnostic) Data Set.

Features
Binary Classification: The model predicts two classes:
0: Malignant
1: Benign
Logistic Regression: A widely used algorithm for binary classification tasks, known for its simplicity and interpretability.
Performance Metrics: The model evaluation includes accuracy, precision, recall, and F1-score.
Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. It consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe the characteristics of the cell nuclei present in the image.

Key Features
Radius: Mean of distances from center to points on the perimeter.
Texture: Standard deviation of gray-scale values.
Perimeter
Area
Smoothness: Local variation in radius lengths.
Compactness: Perimeter^2 / Area - 1.0.
Concavity: Severity of concave portions of the contour.
Concave Points: Number of concave portions of the contour.
Symmetry
Fractal Dimension: "coastline approximation" - 1.
Model Training
Algorithm: Logistic Regression
Training Data: The dataset is split into training and testing sets to evaluate the model's performance. Feature scaling is applied to improve convergence and accuracy.
Cross-Validation: K-fold cross-validation is used to ensure the model generalizes well on unseen data.

Contributing
Contributions are welcome! If you have any ideas, suggestions, or find any issues, feel free to create a pull request or open an issue in this repository.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Dataset: UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Data Set
Scikit-Learn: Python's machine learning library, used for implementing the Logistic Regression model.
Contact
For any questions or inquiries, please contact me at prakritikimothi@gmail.com.

