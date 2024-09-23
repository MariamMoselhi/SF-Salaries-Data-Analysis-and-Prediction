Summary
Data Understanding:

The dataset contains salary information for employees in San Francisco.
Columns such as Id, Notes, and Agency were identified as irrelevant and removed.
Missing and incorrect values in key salary components (BasePay, OtherPay, OvertimePay, Benefits) were handled using median imputation or removal where appropriate.
Data Cleaning:

Non-numeric values in pay columns were converted to numeric.
Missing values in columns like BasePay, OtherPay, and Benefits were filled with medians or removed if they were incomplete.
The dataset was cleaned of unnecessary columns (Notes, Agency, and Status), duplicate rows, and irrelevant entries like Not Provided employee names.
Data Visualization and Preprocessing:

Exploratory visualizations such as box plots, histograms, and heatmaps were used to understand data distribution and correlations between salary components.
Outliers were identified using the IQR method and removed to enhance data quality.
Features were normalized using MinMaxScaler, and categorical job titles were encoded into numeric values.
Feature Selection and Linear Regression:

Features most correlated with TotalPay were selected, excluding non-numeric and less relevant columns.
Linear regression models were built using selected features, and model performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) metrics.
Results showed how feature selection and preprocessing steps impacted model accuracy, providing insights into significant predictors of employee salaries.
