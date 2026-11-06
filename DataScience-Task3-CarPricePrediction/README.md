# Car Price Prediction

## Project Overview
This project uses Machine Learning regression techniques to predict the selling price of a used car based on information such as its age, present price, kilometers driven, fuel type, transmission, and other features.

## Objective
To develop and compare regression models that estimate the selling price of used cars.

## Dataset
- Dataset: CarDekho Used Car Dataset
- Source: [Kaggle – Vehicle Dataset from CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- Target: Selling Price

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Loaded and explored the car dataset.
2. Checked for missing values and duplicate records.
3. Cleaned the data and standardized categorical values.
4. Created additional features such as car age and brand.
5. Performed Exploratory Data Analysis (EDA) using graphs and a correlation heatmap.
6. Selected relevant input features and the target variable.
7. Split the dataset into training and testing sets.
8. Preprocessed numerical and categorical features.
9. Trained two regression models:
   - Linear Regression
   - Random Forest Regressor
10. Evaluated and compared both models.
11. Performed feature importance analysis.
12. Used the selected model to predict the selling price of a sample car.

## Model Evaluation
The models were evaluated using:
               Model       MAE      RMSE  R2 Score
0  Linear Regression  1.348138  2.388979  0.778560
1      Random Forest  1.410843  3.459767  0.535566

## Sample Prediction

A sample car was provided to the trained model to predict its selling price.

**Input:**
- Brand: Honda
- Car Age: 5 years
- Present Price: 8.0 lakhs
- Kilometers Driven: 40,000 km
- Fuel Type: Petrol
- Selling Type: Dealer
- Transmission: Manual
- Previous Owners: 0

**Predicted Output:**
- Estimated Selling Price: ₹6.48 Lakhs (approximately ₹6,48,000)

This prediction demonstrates how the trained model estimates the selling price of a used car based on its features.

## How to Run
1. Clone or download this repository.
2. Keep `car data.csv` in the same folder as the notebook.
3. Open `Car_Price_Prediction.ipynb` in Jupyter Notebook or VS Code.
4. Install the required libraries if they are not already installed.
5. Run all notebook cells in order.

## Project Files
- `Car_Price_Prediction.ipynb` – Project code and analysis.
- `car data.csv` – Dataset used for prediction.
- `screenshots/` – Screenshots of important outputs.

## Conclusion
This project demonstrates how regression algorithms can estimate used car prices using vehicle-related features. Linear Regression and Random Forest Regressor were compared using standard regression evaluation metrics.

## Author
Sachin Kumar