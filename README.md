# analyticsvidhyahackathonproj
Project Summary
Problem: Predict Customer Lifetime Value (CLTV) for an insurance company to identify high-value customers.

Approach:

Data Preprocessing: Cleaned and engineered features, handled categorical variables, and log-transformed the skewed target variable (cltv).
Model Development: Explored Ridge Regression, Random Forest, and XGBoost models.
Optimization: Utilized cross-validation and RandomizedSearchCV for hyperparameter tuning.
Outcome:

Best Model: A tuned XGBoost Regressor achieved the highest performance with a Validation R² of 0.3281 and a minimal overfitting gap.
Key Insights: Identified num_policies, policies_per_year, and income_per_policy as the most influential features.
Deliverable: Generated a verified submission.csv file for the hackathon platform.
