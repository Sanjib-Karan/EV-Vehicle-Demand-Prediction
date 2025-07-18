# EV-Vehicle-Demand-Prediction
EV Vehicle Demand Prediction
This project focuses on forecasting the future adoption of Electric Vehicles (EVs) using historical registration and usage data. With the rapid growth of EVs, understanding future demand is crucial for planning infrastructure such as charging stations and supporting sustainable transportation initiatives.

The workflow includes:

Data Preprocessing: Cleaning missing values, converting dates, and handling outliers using IQR-based capping.

Feature Engineering: Extracting time-based features and encoding categorical variables like County, State, and Vehicle Primary Use.

Model Development: Implemented a Random Forest Regressor optimized with RandomizedSearchCV for accurate predictions.

Evaluation: Assessed model performance using MAE, MSE, and R² Score for robust validation.

This project demonstrates the complete pipeline from raw data to a predictive model, offering insights into EV growth trends to assist in future planning and decision-making.
