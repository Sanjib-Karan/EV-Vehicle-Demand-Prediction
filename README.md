# EV-Vehicle-Demand-Prediction
This project focuses on predicting future demand for electric vehicles (EVs) using historical registration data and regional information. Accurate forecasting is essential for effective infrastructure planning, such as installing charging stations and managing grid capacity for sustainable growth.

**Key Features:**

**Data Preprocessing**: Cleaned missing values, standardized date formats, and converted numeric columns.

**Outlier Handling**: Applied IQR-based capping to maintain data quality without removing useful records.

**Feature Engineering**: Extracted time-based trends and preserved categorical attributes like state and county.

**Modeling**: Implemented a Random Forest Regressor with hyperparameter tuning using ***RandomizedSearchCV***.

**Evaluation**: Measured performance using MAE, MSE, and R² for comprehensive assessment.
