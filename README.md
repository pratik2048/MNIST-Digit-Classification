# MNIST Digit Classification using PCA and KNN

## Project Overview

This project uses Machine Learning to classify handwritten digits from the MNIST dataset.

The project uses Principal Component Analysis (PCA) for dimensionality reduction and K-Nearest Neighbors (KNN) for classification.

## Dataset

The MNIST dataset contains 70,000 handwritten digit images.

- 70,000 samples
- 784 pixel features
- 28 × 28 pixel images
- 10 classes (0–9)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Workflow

1. Load the MNIST dataset
2. Explore the dataset
3. Visualize handwritten digits
4. Separate features and target
5. Split the dataset into training and testing data
6. Standardize the features using StandardScaler
7. Apply PCA
8. Train KNN classifier
9. Make predictions
10. Calculate accuracy

## Preprocessing

StandardScaler is used to standardize the pixel features.

PCA is used to reduce the number of features from 784 to 100 components.

## Machine Learning Model

The classification algorithm used in this project is:

**K-Nearest Neighbors (KNN)**

## Evaluation

The model is evaluated using:

- Accuracy Score

## Project Files

- `MNIST_Digit_Classification.ipynb` — Complete Jupyter Notebook
- `README.md` — Project documentation
