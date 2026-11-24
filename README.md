# CIE2 RCA UT1 Project – Diabetes Dataset Analysis

## About the Project

This project focuses on Exploratory Data Analysis (EDA) and Regression Model Development using the Diabetes dataset available in Scikit-learn.

The project uses Random Forest Regression to predict diabetes disease progression and evaluates the model's performance.

## Objective

To perform data exploration and develop a Random Forest Regression model using the Diabetes dataset.

## Dataset

- Dataset Name: Diabetes Dataset
- Source: Scikit-learn
- Type: Regression Dataset
- Target Variable: Disease_Progression

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Experiment Workflow

### 1. Import Libraries
Import the required Python libraries for data analysis, visualization and machine learning.

### 2. Load Dataset
Load the Diabetes dataset using Scikit-learn and convert it into a Pandas DataFrame.

### 3. Data Understanding
- Display the first few records.
- Check dataset shape.
- Check column information.
- Generate descriptive statistics.

### 4. Exploratory Data Analysis (EDA)
- Analyze the dataset.
- Check correlation between features.
- Visualize data using graphs.
- Use box plots to observe outliers.

### 5. Data Preprocessing
Prepare the dataset for machine learning model development.

### 6. Train-Test Split
Split the dataset into:
- 80% Training Data
- 20% Testing Data

### 7. Model Development

**Algorithm:** Random Forest Regressor

Model Parameters:
- n_estimators = 200
- max_depth = 5
- min_samples_split = 4
- random_state = 42

### 8. Model Evaluation

Evaluate the model using the following metrics:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

### 9. Baseline Model Comparison

Use Dummy Regressor as a baseline model and compare its performance with the Random Forest Regressor.

### 10. Data Visualization

Generate the following visualizations:

- Actual vs Predicted Values
- Feature Importance Graph

## Project Structure

```text
CIE2-RCA-UT1-Project/
│
├── CIE2_RCA_UT1_PROJECT_.ipynb
│
└── README.md
```
#[ DIPANSHU SAGAR SIR ](https://github.com/complexiota)
