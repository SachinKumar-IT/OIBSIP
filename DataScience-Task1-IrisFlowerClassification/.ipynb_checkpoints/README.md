# Iris Flower Classification

## Project Overview
This project uses Machine Learning to classify iris flowers into three species: Setosa, Versicolor, and Virginica, based on their physical measurements.

## Objective
To build and evaluate classification models that can predict the species of an iris flower using its sepal and petal measurements.

## Dataset
- Dataset: Iris Flower Dataset
- Source: Built-in dataset from Scikit-learn
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target: Iris Species (Setosa, Versicolor, Virginica)

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Loaded the Iris dataset using Scikit-learn.
2. Explored the dataset using Pandas.
3. Performed Exploratory Data Analysis (EDA) using visualizations.
4. Split the dataset into training and testing sets.
5. Standardized the feature values.
6. Trained two classification models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
7. Evaluated the models using accuracy, confusion matrix, and classification report.
8. Selected the better-performing model and tested a sample prediction.

## Model Evaluation
The models were evaluated using:
- Logistic Regression
- K-Nearest Neighbors (KNN)

Evaluation Metrics:
- Logistic Regression Accuracy: 93.33%
- KNN Accuracy: 93.33 %

## Sample Prediction

The model was tested with the following flower measurements:

**Input:**
- Sepal Length: 5.1 cm
- Sepal Width: 3.5 cm
- Petal Length: 1.4 cm
- Petal Width: 0.2 cm

**Predicted Output:**
- Iris Species: Setosa

The model successfully predicted the flower species based on its measurements.

## How to Run
1. Clone or download this repository.
2. Open `Iris_Flower_Classification.ipynb` in Jupyter Notebook or VS Code.
3. Install the required libraries if they are not already installed.
4. Run all notebook cells in order.

## Project Files
- `Iris_Flower_Classification.ipynb` – Project code and analysis.
- `screenshots/` – Screenshots of important outputs.

## Conclusion
This project demonstrates how classification algorithms can be used to identify iris flower species from their physical measurements. The performance of Logistic Regression and KNN was compared to select the better model.

## Author
Sachin Kumar