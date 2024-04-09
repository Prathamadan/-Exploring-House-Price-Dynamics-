# EXPLORING HOUSE PRICE DYNAMICS  
!['House Price Prediction'](https://miro.medium.com/v2/resize:fit:1400/1*3Psu7nDr2LvhWH4R6-Tqeg.jpeg)  

## Overview
This project aims to predict house prices using machine learning techniques. It involves data understanding and exploration, data cleaning, data preparation, model building, and evaluation.

## Project Structure
The project is divided into the following sections:

- Data Understanding and Exploration: In this section, we load the dataset, explore the data by examining the first few rows, checking the shape and information of the dataset, and identifying null values.

- Data Cleaning: This section focuses on treating null values and dropping variables with a high percentage of missing values. We also handle outliers and multicollinearity among features.

- Data Preparation: Here, we perform univariate analysis to understand the distribution of data and prepare the dataset for modeling. This includes creating dummy variables for categorical features and scaling numerical features using MinMaxScaler.

- Model Building and Evaluation: In this final section, we split the data into training and testing sets, apply various regression models including Linear Regression, Ridge Regression, and Lasso Regression. We evaluate the models using performance metrics such as R-squared score, RSS, and RMSE. We also analyze feature importance and provide insights into model selection.

## Files
- train.csv: The dataset containing house prices and various features.  
- EXPLORING_HOUSE_PRICE_DYNAMICS.ipynb: Jupyter Notebook containing the Python code for the entire project.  
- README.md: This README file providing an overview of the project.

## Libraries Used:
1. NumPy  
2. Pandas  
3. Matplotlib  
4. Seaborn  
5. Scikit-learn  
6. Statsmodels  

## How to Run
To run the project:

1. Ensure you have Python installed on your system.    
2. Install the required libraries using pip install -r requirements.txt.  
3. Open the Jupyter Notebook "EXPLORING_HOUSE_PRICE_DYNAMICS.ipynb".  
4. Run the notebook cell by cell to execute the code and observe the results.  

## Conclusion
The project demonstrates the process of predicting house prices using machine learning techniques. It showcases data cleaning, preparation, model building, and evaluation steps, providing insights into the importance of feature selection and regularization techniques like Ridge and Lasso Regression. The final model selection is based on performance metrics and feature importance analysis.
