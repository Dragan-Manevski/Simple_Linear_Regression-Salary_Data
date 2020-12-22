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
