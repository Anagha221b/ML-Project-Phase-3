# ML-Project-Phase-3

Hyperparameter Tuning and Comparative Analysis of Machine Learning Models for Predicting Energy Billing Amounts

Columns and their description in the dataset:

customer_id: Unique identifier for each customer.

region: Geographic region of the customer.

energy_consumption_kwh: Total energy consumption in kilowatt-hours.

peak_hours_usage: Energy usage during peak hours

off_peak_usage: Energy usage during off-peak hours

renewable_energy_pct: Percentage of energy from renewable sources.

billing_amount**: Total billing amount.

household_size**: Number of people in the household.

temperature_avg**: Average temperature.

income_bracket**: Income bracket of the household.

smart_meter_installed**: Whether a smart meter is installed

time_of_day_pricing**: Whether time-of-day pricing is used.

annual_energy_trend**: Annual trend in energy consumption

solar_panel**: Whether solar panels are installed.

target_high_usage**: Whether the household is targeted for high usage.

Steps for Hyperparameter Tuning

Define the Parameter Grid: Specify the range of hyperparameters to be tested.

Initialize GridSearchCV: Use GridSearchCV to perform an exhaustive search over the specified parameter grid.

Fit the Model: Train the model using the training data.

Evaluate the Best Model: Evaluate the performance of the best model found during the search.

Explanation:
Parameter Grid: Define the range of hyperparameters for Random Forest and Decision Tree.

GridSearchCV Initialization: Initialize GridSearchCV with the estimator, parameter grid, cross-validation strategy, and other settings.

Model Fitting: Fit the model using the training data.

Best Parameters and Score: Retrieve the best parameters and cross-validation score.

Model Evaluation: Evaluate the best model on the test set and print the Mean Squared Error (MSE) and R-squared (R²) score.

