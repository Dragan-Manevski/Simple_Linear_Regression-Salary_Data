### --------------------------------------------------------------------------------------------------------
# Simple Linear Regression - Salary Data
### --------------------------------------------------------------------------------------------------------
### Linear Regression:
- an **algorithm**:
    - based on **Supervised Learning**
    - where machines **learn with supevision**
    - **input data are labeled** and **expected output data is known**
    - used **to predict continuous (quantitative) numeric output value (y) based on given continuous (quantitative) numeric input variable(s) (x)**
    - where using the **linear relationship between numeric dependent output variable (y) (target) and independent input variable(s) (x) (predictor(s))**, we try **to find the best fit line (equation)** that can be used to make predictions
    - **best fit line** is known as **Regression line** and is represented by a **linear equation**:
                                        
                                        Y = a * X + b
                              where,

                                        Y - dependent variable we are trying to predict
                                        X - independent variable we are using to make predictions
                                        a, b - coefficients of Linear Regression equation (line)
                                        a - slope, which represents the effect X has on Y
                                        b - intercept, which is a constant

- **regression analysis** is a **predictive modelling technique**
- **types** of Linear Regression:
  - **Simple Linear Regression** is a linear relationship between a single independent input variable (x) and corresponding dependent output variable (y)
  - **Multiple Linear Regression** is a linear relationship between 2 or more independent input variables (x) and corresponding output dependent variable (y)
- **examples** of Linear Regression problems: 						
  - House price				
  - Weather forcast				
  - Process optimization
  - Number of calls
  - Total sales
### --------------------------------------------------------------------------------------------------------
### Project Objective: Predicting salary of employee
Create a model that allows to return back an estimate of the salary of an employee given how many years of experience they have. Information about the salaries is in the dataset 'Salary_Data.csv' of 'Data' folder.

The Salary Data dataset contains the following columns:
- **YearsExperience** - number of years of experience (independent variable)
- **Salary** - respective salary of each employee (dependent variable)

### --------------------------------------------------------------------------------------------------------
### Table of Contents
1. File Descriptions
2. Technologies Used
3. Structure of Notebook
4. Executive Summary

### --------------------------------------------------------------------------------------------------------
#### 1. File Descriptions
-**Data** : folder containing all data files
-**Images** : folder containing images used for README
-**Models** : folder containing trained models saved with pickle

### --------------------------------------------------------------------------------------------------------
#### 2. Technologies Used
-**Python**
-**Pandas**
-**Numpy**
-**Matplotlib**
-**Seaborn**
-**Scikit-Learn**

### --------------------------------------------------------------------------------------------------------
#### 3. Structure of Notebook
1. Import the Libraries
2. Load the Data
3. Exploratory Data Analysis
    3.1 Check out the Data
    3.2 Data Visualization
4. Data Preprocessing and Feature Engineering
    4.1 Identify the variables
    4.2 Dealing with Missing values
    4.3 Dealing with Outliers
5. Train and Test the Linear Regresion model
    5.1 Split the columns
    5.2 Split the data into Training dataset and Testing dataset
    5.3 Create the Linear Regression model
    5.4 Train / fit the Linear Regression model
    5.5 Calculate the coefficients of Linear Regression equation
    5.6 Predictions from the model on Testing data
    5.7 Evaluate the model on Testing data
6. Predict the label on new data

### --------------------------------------------------------------------------------------------------------
#### 4. Executive Summary
TBA
