# House Prices - Regression Project

This project predicts house prices in Ames, Iowa, based on a rich dataset of property features.

## Project Overview
The goal of the project was to perform structured data exploration, clean and prepare the data, engineer features when necessary, and build a predictive model using **Linear Regression**.  
Special emphasis was placed on understanding feature distributions, handling skewed data, and preparing the dataset for reliable model training and evaluation.

Key steps:
- Data loading and initial exploration.
- Identification and removal of categorical features to simplify modeling.
- Handling missing values through column and row removal strategies.
- Feature distribution analysis via histograms to detect skewness and outliers.
- Logarithmic transformation of skewed features to improve linearity and model stability.
- Standardization (Z-score scaling) of numerical features to ensure balanced input for the model.
- Model training, validation, and evaluation using Root Mean Squared Error (RMSE).

## Tools and Technologies
- **Python** – for all stages of data handling and modeling.
- **Pandas** – for dataset manipulation and preprocessing.
- **NumPy** – for mathematical operations and transformations.
- **Matplotlib** and **Seaborn** – for graphical exploration of feature distributions and correlations.
- **Scikit-learn** – for preprocessing steps, model building (Linear Regression), and performance evaluation.

## How it Works
1. Loaded and explored the dataset to identify numerical vs. categorical features.
2. Dropped categorical features to streamline the dataset for linear modeling.
3. Detected and addressed missing values by removing problematic columns and rows.
4. Analyzed feature distributions and correlations with the target (`SalePrice`) to guide feature selection and transformation.
5. Applied log transformation to highly skewed features to improve feature linearity.
6. Standardized numerical features using Z-score scaling to normalize their impact on the model.
7. Trained a **Linear Regression** model, tuned it through cross-validation, and evaluated performance based on RMSE.
8. Submitted final predictions on a separate test set.

## Key Highlights
- **Comprehensive Data Cleaning**: Addressed missing values and reduced dataset complexity.
- **Data Transformation Expertise**: Applied logarithmic correction for skewed distributions, a key aspect of linear model preparation.
- **Effective Data Scaling**: Ensured consistent feature scaling to improve model training and convergence.
- **Data-Centric Decision Making**: Every transformation step was backed by statistical exploration and visualization insights.
- **Robust Evaluation**: Used RMSE and cross-validation to ensure stable, generalized model performance.

## Dataset
- [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

---

> *This project showcases strong capabilities in data exploration, preprocessing, transformation, and regression modeling — skills fundamental to modern Data Engineering and Analytics roles.*
