# Linear-Regression
Linear Regression – Description 🎯 Objective To implement and understand both Simple Linear Regression and Multiple Linear Regression using Python libraries to predict house prices based on features such as square footage, bedrooms, bathrooms, and floors.

🧰 Technologies Used
Pandas – for data loading and preprocessing

Scikit-learn (sklearn) – for model training and evaluation

Matplotlib – for plotting the regression line

NumPy – for numerical operations

🗃️ Dataset
House Price Prediction Dataset
Download: Kaggle - House Sales in King County, USA
It includes features like:

sqft_living (size of house)

bedrooms

bathrooms

floors

price (target)

🔍 Workflow Summary
✅ 1. Import & Preprocess Data
Load the dataset using pandas

Select relevant features for regression

Handle missing values

✅ 2. Simple Linear Regression
Use only sqft_living as a single feature

Train model using LinearRegression()

Evaluate using:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

Plot the regression line with actual data

✅ 3. Multiple Linear Regression
Use multiple features: sqft_living, bedrooms, bathrooms, floors

Train and evaluate similarly as above

Output model coefficients for interpretation

📈 Output & Interpretation
Intercept: Base price prediction when all features are 0

Coefficients: Change in price per unit increase in each feature

R² Score: Model performance metric; closer to 1 means better fit


