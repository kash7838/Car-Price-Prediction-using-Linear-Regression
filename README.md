## Project Overview
- --
- Built a regression model to predict car prices based on features like brand, mileage, engine volume, and year.

- Applied statistical preprocessing, outlier removal, and log transformation to improve model accuracy.

- Evaluated assumptions of OLS regression and validated results with residual analysis.

## Dataset
- --
- Car sales dataset with ~4,300 records and features such as brand, price, body type, mileage, engine volume, engine type, registration status, and year.

- Cleaned dataset reduced to ~3,800 records after handling missing values and outliers.

## Steps Implemented
- --
- Data Cleaning: Removed missing values, handled outliers (top 1% of price, mileage, unrealistic engine volumes).

- Feature Engineering: Log transformation of price, dummy variables for categorical features.

- Multicollinearity Check: Used Variance Inflation Factor (VIF) to drop highly correlated features.

- Modeling: Trained a log‑linear regression model using scikit‑learn.

- Evaluation: Achieved R² ≈ 0.755 on training data, residuals approximately normally distributed.
  
## Results
- Mileage negatively impacts car price.

- Engine volume positively impacts car price.

- Certain brands and body types show significant negative weights compared to baseline.

- Registration status increases predicted price.
-
- --
- Developed a car price prediction model using Python (Pandas, scikit‑learn, Statsmodels) with end‑to‑end preprocessing, feature engineering, and regression analysis.

- Improved model accuracy (R² = 0.755) by handling missing values, removing outliers, applying log transformation, and checking OLS assumptions.

- Delivered actionable insights on how mileage, engine volume, brand, and registration status influence car resale value.






