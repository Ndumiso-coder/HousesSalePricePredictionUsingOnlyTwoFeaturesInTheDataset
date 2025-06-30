# Linear regression on Ames housing dataset.
This project performs a simple multiple linear regression on the Ames Housing dataset using two features: **Gr_Liv_Area** and **Garage_Area** to predict **SalePrice**. 
All analysis is conducted in a Jupyter Notebook: **Linear_Regression_Ames_2.ipynb**.

---

##  Objective

To analyse the relationship between the three (Gr_Liv_Area, Garage_Area and Sale_Price) variables and build a multiple linear regression model to predict
the sales prices based on the Gr_Liv_Area and Garage_Area variables.

---

## Workflow Summary

### 1. Load and preview the Data.
- Read ames.csv into a DataFrame using pandas.

### 2. Data Cleaning & Preparation
- Handled missing & duplicate values and ensured data types were correct for modeling.

### 3. Exploratory Data Analysis (EDA)
- Visualized the relationship between the three columns of interest using a correlation matrix

### 4. Feature Selection
- Selected Gr_Liv_Area and Garage_Area as independent variables (predictors).
- Set SalePrice as the dependent variable (the response).

### 5. Build simple linear regression models for each independent variable vs the dependent variable.

### 6. Create a multimple linear regression

### 7. Data Splitting
- Split the dataset into training and test sets (75% train, 25% test).

### 8. Visualising the distribution of the data before data scaling
- Plot a pairplot of our independent variables to visualise their distribution
- Use normalizing to scale the data because it does not follow a Gaussian' distribution.


### 9. Fit the model on the training data
- Trained a Multiple Linear Regression model using `LinearRegression()` from `scikit-learn`.

### 10. Model Parameters
- Printed model intercept and coefficients.

### 11. Prediction & Evaluation
- Predicted sale prices on the test set.
- Evaluated model using:
  - Mean Squared Error (MSE)
  
### 12. Error Visualization
- Plotted predicted vs actual values to show model performance.

### 13. Interpretation
- Interpreted coefficients to understand the effect of each variable on price.

---

## Tools Used

- Python              - programming language
- Jupyter Notebook    - an interactive environment
- pandas              - for data manipulation and analysis
- numpy               - for numerical computation
- matplotlib          - for plotting
- seaborn             - for plotting
- scikit-learn        - Machine learning library used to: - Split the dataset into training and test sets, build and train the linear regression model, generate predictions, evaluate the model (MSE)

---

## Key Insights

- Strong positive correlation between living area and sale price.
- Garage area also contributes to predicting sale price, but to a lesser extent.
- More features may be added to our model to improve performance.
