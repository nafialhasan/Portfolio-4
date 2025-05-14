# Portfolio 4: Analysis of Car Price Prediction Data

This repository contains my solutions for the Portfolio 4 assignment for the course COMP6200 – Data Science. The assignment involves analyzing a car price prediction dataset to predict car prices using various regression models, and evaluating the strengths and weaknesses of these models.

## Contents

- `Portfolio 4_Analysing Car Price Prediction.ipynb`: The Jupyter notebook containing the questions, solutions, code, and analysis for Portfolio 4.
- `car_price_prediction.csv`: The dataset used for this analysis.

## Assignment Details

### Analysis of Car Price Prediction Data

The goal of this analysis task is to train regression models to predict car prices ('Price' in the dataset) and evaluate the strengths and weaknesses of these models. The dataset contains details about car features and prices.

#### Dataset Description

The dataset includes the following fields:

- **ID**: Unique ID
- **Price**: Price of the car (Target Column)
- **Levy**: Fees or taxes charged on the vehicle
- **Manufacturer**: Maker of the car
- **Model**: Model name
- **Prod. year**: Production year
- **Category**: Type of vehicle
- **Leather interior**: Has leather interior or not (Yes/No)
- **Fuel type**: Type of fuel the vehicle uses
- **Engine volume**: Power of the engine
- **Mileage**: km driven
- **Cylinders**: Number of cylinders in the engine
- **Gear box type**: Type of gearbox the vehicle has
- **Drive wheels**: Type of drivetrain
- **Doors**: Number of doors the vehicle has
- **Wheel**: Driving orientation
- **Color**: Color of the vehicle
- **Airbags**: Number of airbags the vehicle has

### Tasks and Solutions

#### 1. Exploratory Data Analysis
**Task:** Explore the dataset by examining its shape, summary statistics, and missing values. Handle any abnormal instances or outliers.
- **Actions:**
  - Checked the shape and descriptive statistics of the dataset.
  - Converted categorical data to numeric format using `OrdinalEncoder`.
  - Visualized the distributions and relationships between features and the target variable.

#### 2. Feature Selection and Correlation Analysis
**Task:** Study the correlation between 'Price' and other features, and select relevant features.
- **Actions:**
  - Calculated the correlation coefficients between 'Price' and other variables.
  - Selected the five most correlated features: `Doors`, `Mileage`, `Category`, `Gear box type`, and `Wheel`.

#### 3. Data Splitting
**Task:** Split the dataset into training (75%) and test (25%) sets.
- **Actions:**
  - Used `train_test_split` to split the data.

#### 4. Model Building, Training, and Evaluation
**Task:** Train regression models to predict 'Price' based on the selected features.
- **Models Trained:**
  - **Linear Regression**
  - **Polynomial Regression**
  - **Decision Tree Regression**
- **Actions:**
  - Trained each model and calculated evaluation metrics (MAE, MSE, RMSE, R2).
  - Evaluated and compared the performance of each model.

#### 5. Visualization and Analysis
**Task:** Visualize the results and analyze the findings.
- **Actions:**
  - Plotted residuals vs. predicted values for each model.
  - Created bar graphs to compare evaluation metrics across models.
  - Interpreted the results and identified insights.

## Repository Structure

- `README.md`: This file, providing an overview of the repository contents and assignment details.
- `Portfolio 4_Analysing Car Price Prediction.ipynb`: The main assignment file containing questions, solutions, code, and analysis.
- `car_price_prediction.csv`: The dataset used for the analysis.

## Contact Information
For any queries or further information, feel free to contact me at [nafialhasan@gmail.com](mailto:nafialhasan@gmail.com).  
You can also connect with me on [LinkedIn](https://www.linkedin.com/in/nafialhasan/).
