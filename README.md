# Deepflow
**Mini Project 1 :**
- **Name**: Zomato Dataset
- **Source**: `data.xlsx`
- **Description**: The dataset contains information about restaurants, such as names, locations, ratings, cuisines, and cost.

Dataset Loading :
The Zomato dataset is loaded from a local Excel file (data.xlsx) into a Pandas DataFrame for further processing.

Initial Exploration :
Basic functions like df.info(), df.head(), and df.shape are used to understand the dataset’s structure, data types, and overall size.

Missing Value Handling :
The dataset is checked for missing values, which are then handled appropriately—either by removing incomplete entries or filling them with meaningful defaults.

Data Cleaning & Feature Engineering :
Unnecessary columns may be dropped, duplicates removed, and categorical data encoded. These steps help prepare the dataset for analysis and modeling.

Exploratory Data Analysis (EDA) :
Graphs and visualizations are created to explore key patterns and relationships in the data.

**Major Project 2 : Bulldozer Sale Price Prediction**

**Objective:** : Build a regression model that predicts the sale price of bulldozers and other heavy equipment at auction using structured data.

**Tasks Performed:**
- Data cleaning and preprocessing (handling missing values, outliers, encoding)
- Feature engineering from saledate
- Model training using:
Linear Regression,
Random Forest Regressor,
XGBoost Regressor
- Model evaluation using Root Mean Squared Logarithmic Error (RMSLE)
- Prediction on test set
- Output CSV submission file: test_predictions.csv
