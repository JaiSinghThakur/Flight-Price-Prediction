# Flight Price Prediction — Machine Learning Project

## Overview
This project predicts airline ticket prices using a complete Machine Learning workflow.  
It includes data cleaning, exploratory data analysis (EDA), feature engineering, model building, hyperparameter tuning, and evaluation.

---

## Project Structure
- **01_EDA.ipynb** – Exploratory Data Analysis  
- **02_Feature_Engineering.ipynb** – Data preprocessing & encoding  
- **03_Model_Building.ipynb** – Model training and tuning  
- **data/Clean_Dataset_Final.csv** – Cleaned dataset  
- **README.md** – Project documentation  

---

## Steps Performed

### 1. Data Cleaning
- Removed unnecessary columns  
- Checked missing values and duplicates  
- Exported cleaned dataset  

### 2. Exploratory Data Analysis (EDA)
- Visualized price distribution  
- Analyzed airlines, cities, class, stops, timings  
- Checked correlations  
- Identified important factors affecting prices  

### 3. Feature Engineering
- Label encoding and One-hot encoding  
- Converted categorical features to numeric  
- Removed unused columns  
- Exported final processed dataset  

### 4. Model Building
- Used RandomForestRegressor  
- Train/test split  
- Evaluated using R², MAE, MSE, RMSE  
- Plotted predicted vs actual values  
- Checked feature importance  

### 5. Hyperparameter Tuning
Performed using RandomizedSearchCV.

**Best parameters found:**

