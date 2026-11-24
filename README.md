# California Housing Price Prediction using Linear Regression

## Project Overview
This project predicts California house prices using the California Housing Prices dataset from Kaggle. It uses Multiple Linear Regression, Ridge Regression, and Lasso Regression to train and compare different regression models.

## Dataset
- **Dataset Name:** California Housing Prices
- **Source:** Kaggle
- **Dataset:** `camnugent/california-housing-prices`
- **Rows:** Approximately 20,640
- **Target Variable:** `median_house_value`

## Objectives
1. Load the California Housing dataset using KaggleHub.
2. Perform data understanding and exploratory data analysis (EDA).
3. Handle missing values using median imputation.
4. Inspect outliers using box plots.
5. Perform feature engineering using ratio features.
6. Encode categorical data using One-Hot Encoding.
7. Split the dataset into training and testing sets.
8. Apply feature scaling using StandardScaler.
9. Train and compare Linear Regression, Ridge, and Lasso models.
10. Evaluate model performance using regression metrics.

## Technologies and Libraries Used
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

## Project Workflow

### 1. Data Loading
Loaded the California Housing Prices dataset from Kaggle using KaggleHub.

### 2. Data Cleaning
- Checked missing values and duplicate records.
- Replaced missing values in `total_bedrooms` with the median.

### 3. Exploratory Data Analysis
- Used statistical summaries.
- Created box plots to inspect outliers.
- Used a correlation heatmap.
- Created scatter plots to understand relationships between features and house prices.

### 4. Feature Engineering
Created three new features:
- `rooms_per_household`
- `bedrooms_per_room`
- `population_per_household`

### 5. Data Preprocessing
- Applied One-Hot Encoding to `ocean_proximity`.
- Used an 80:20 train-test split.
- Applied StandardScaler to scale the features.

### 6. Model Training
Implemented and compared three models:
- Multiple Linear Regression (OLS)
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

### 7. Model Evaluation
Evaluated models using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- 5-Fold Cross Validation

### 8. Visualization
Created diagnostic plots:
- Actual vs Predicted Values
- Residuals vs Fitted Values
- Residual Distribution
- Feature Coefficients

## Important Findings
- Median income is a strong positive predictor of house prices.
- Location-related features influence house prices.
- Ridge and Lasso regularization help control the effects of multicollinearity.
- The three regression models are compared to understand their performance.

## How to Run the Project

1. Download or clone this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

4. Run the notebook cells from top to bottom.
5. Make sure you have access to Kaggle to download the dataset through KaggleHub.

## Project File

`RCA_PROJECT_1_Linear_Regression.ipynb`

## Conclusion
This project demonstrates the complete machine learning workflow for predicting California house prices using Linear Regression and regularization techniques. It includes data preprocessing, feature engineering, model training, evaluation, cross-validation, and visualization.

---
**Project Type:** Machine Learning – Regression  
**Dataset:** California Housing Prices  
**Language:** Python
```text
CIE2-RCA-UT1-Project/
│
├── CIE2_RCA_UT1_PROJECT_.ipynb
│
└── README.md
```
#[ DIPANSHU SAGAR SIR ](https://github.com/complexiota)
