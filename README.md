# AI-ML-Task-6

## By Abhishek Mitra

# KNN Classification on Iris Dataset

This project demonstrates the use of the K-Nearest Neighbors (KNN) algorithm to classify species in the classic Iris dataset. The workflow includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

![image](https://github.com/user-attachments/assets/ecf830c9-eaee-45d0-941b-52dbad7c22f7)


## Files

- [`Iris.csv`](Iris.csv): The dataset containing measurements of iris flowers and their species.
- [`knn.ipynb`](knn.ipynb): Jupyter notebook implementing the KNN classification, accuracy analysis, confusion matrix, and decision boundary visualization.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies with:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Open `knn.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells to:
   - Load and preprocess the data
   - Train and evaluate KNN models for different values of K
   - Visualize accuracy and confusion matrix
   - Plot decision boundaries for the first two features

## Project Steps

- **Data Loading:** Reads `Iris.csv` into a pandas DataFrame.
- **Preprocessing:** Standardizes features and splits data into training and test sets.
- **Model Training:** Trains KNN classifiers for K=1 to 10, records accuracy and confusion matrices.
- **Evaluation:** Plots accuracy vs. K and displays the confusion matrix for the best K.
- **Visualization:** Shows decision boundaries using the first two standardized features.
