This project performs a simple multiple linear regression on the Ames Housing dataset using two features: **Gr_Liv_Area** and **Garage_Area** to predict **SalePrice**. All analysis is conducted in a Jupyter Notebook: `Linear_Regression_Ames.ipynb`.

---

## 📁 Project Files

- `ames.csv` — Dataset file.
- `Linear_Regression_Ames.ipynb` — Jupyter notebook with full analysis.
- `README.md` — Project overview and documentation.

---

## 🎯 Objective

Predict housing sale prices based on:
- `Gr_Liv_Area` (above ground living area in square feet)
- `Garage_Area` (garage size in square feet)

---

## 📊 Workflow Summary

### ✅ 1. Load the Data
- Read `ames.csv` into a DataFrame using pandas.

### ✅ 2. Data Cleaning & Preparation
- Handled missing values and ensured data types were correct for modeling.

### ✅ 3. Exploratory Data Analysis (EDA)
- Visualized the distributions of:
  - `SalePrice` (dependent variable)
  - `Gr_Liv_Area` and `Garage_Area` (independent variables)
- Used histograms and scatter plots to detect trends and outliers.

### ✅ 4. Feature Selection
- Selected `Gr_Liv_Area` and `Garage_Area` as predictors.
- Set `SalePrice` as the response variable.

### ✅ 5. Data Splitting
- Split the dataset into training and test sets (75% train, 25% test).

### ✅ 6. Model Training
- Trained a Multiple Linear Regression model using `LinearRegression()` from `scikit-learn`.

### ✅ 7. Model Parameters
- Printed model intercept and coefficients.

### ✅ 8. Prediction & Evaluation
- Predicted sale prices on the test set.
- Evaluated model using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

### ✅ 9. Error Visualization
- Plotted predicted vs actual values to show model performance.

### ✅ 10. Interpretation
- Interpreted coefficients to understand the effect of each variable on price.

---

## 📈 Example Output (replace with your actual results)

| Metric | Value |
|--------|--------|
| MSE    | 2.13e+09 |
| RMSE   | 46,161.23 |

---

## 🧰 Tools Used

- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 💡 Key Insights

- Strong positive correlation between living area and sale price.
- Garage area also contributes to predicting sale price, but to a lesser extent.
