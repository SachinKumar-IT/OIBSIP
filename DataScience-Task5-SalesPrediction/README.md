# Sales Prediction Using Python

## Project Overview
This project uses Machine Learning regression techniques to predict product sales based on advertising expenditure across three channels: TV, Radio, and Newspaper.

## Objective
To analyse the relationship between advertising expenditure and sales, and build models that can predict sales using advertising budgets.

## Dataset
- Dataset: Advertising Dataset
- Source: [Kaggle – Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
- Input Features: TV, Radio, Newspaper
- Target: Sales

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Loaded and explored the advertising dataset.
2. Checked for missing values and duplicate records.
3. Cleaned the dataset.
4. Performed Exploratory Data Analysis (EDA).
5. Created scatterplots to study the relationship between advertising expenditure and sales.
6. Generated a correlation heatmap.
7. Split the dataset into training and testing sets.
8. Trained two regression models:
   - Linear Regression
   - Random Forest Regressor
9. Evaluated and compared both models.
10. Analysed Linear Regression coefficients and Random Forest feature importance.
11. Created a residual plot for the selected best-performing model.
12. Predicted sales using sample advertising expenditure values.

## Model Evaluation
The models were evaluated using:
               Model       MAE      RMSE  R2 Score
0  Linear Regression  1.274826  1.705215  0.905901
1      Random Forest  0.918000  1.198930  0.953483

## Feature Analysis
The project analyses the impact of TV, Radio, and Newspaper advertising expenditure on sales using model coefficients and feature importance.

Most Impactful Advertising Channel: Radio

## Sample Prediction

A sample advertising budget was provided to the trained model to predict product sales.

**Input:**
- TV Advertising Budget: 150
- Radio Advertising Budget: 25
- Newspaper Advertising Budget: 20

**Predicted Output:**
- Predicted Sales: 14.9

This prediction demonstrates how advertising expenditure across different channels can be used to estimate product sales.

## How to Run
1. Clone or download this repository.
2. Keep `Advertising.csv` in the same folder as the notebook.
3. Open `Sales_Prediction.ipynb` in Jupyter Notebook or VS Code.
4. Install the required libraries if they are not already installed.
5. Run all notebook cells in order.

## Project Files
- `Sales_Prediction.ipynb` – Project code and analysis.
- `Advertising.csv` – Dataset used for prediction.
- `screenshots/` – Screenshots of important outputs.

## Conclusion
This project demonstrates how Machine Learning regression models can be used to predict sales based on advertising expenditure. It also helps analyse the relationship between different advertising channels and sales performance.

## Author
Sachin Kumar