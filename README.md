# SCT_ML_01
This project demonstrates how to predict house prices using supervised machine learning regression algorithms. The workflow involves data cleaning, exploratory data analysis, feature scaling and encoding, model training with different regressors, and evaluation using standard metrics.

## Dataset

The dataset used is typically called `Housing.csv` and contains the following features for each house:
- `price` (target)
- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- `mainroad`
- `guestroom`
- `basement`
- `hotwaterheating`
- `airconditioning`
- `parking`
- `prefarea`
- `furnishingstatus`

## Features

- Data import and missing value handling
- Outlier removal using Z-score
- Correlation analysis and visualization
- Feature scaling (StandardScaler)
- Encoding categorical variables (LabelEncoder)
- Model building with:
  - K-Nearest Neighbors (KNN)
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Model evaluation with Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score
- Data visualization (heatmaps, regression plots)

## Project Workflow

1. **Data Loading**  
   Load housing data from CSV.

2. **Exploratory Data Analysis (EDA)**  
   - View first few rows
   - Check for missing values
   - Visualize correlation with a heatmap

3. **Data Cleaning**  
   - Remove missing values if any
   - Remove outliers using Z-score

4. **Feature Engineering**  
   - Encode categorical variables
   - Scale numeric features

5. **Model Training & Evaluation**  
   - Split data into training and testing sets
   - Train and evaluate KNN, Linear Regression, Decision Tree, and Random Forest models
   - Compare performance using MSE, MAE, and R² scores

6. **Visualization**  
   - Plot actual vs. predicted prices

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- scipy
- jupyter
