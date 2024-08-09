# Black Friday Sales Prediction

## Objective
This project aims to predict customer purchase amounts across various products based on customer demographics and product details. The goal is to develop predictive models that can help create personalized offers and optimize marketing strategies.

## Dataset
The dataset includes:
- **Customer Demographics**: Age, Gender, Marital Status, City Type, and Stay in Current City Years.
- **Product Details**: Product ID and Product Categories.
- **Target Variable**: Purchase Amount.

## Preprocessing Steps
1. **Data Cleaning**: Handled missing values and removed outliers.
2. **Categorical Encoding**: Converted features such as 'Gender', 'Age', and 'Stay in Current City Years' into numerical representations using methods like binary encoding and mapping.

## Exploratory Data Analysis (EDA)
1. **Purchase Amount Distribution**: Analyzed the distribution of purchase amounts and identified any outliers.
2. **Feature Analysis**: Performed analyses based on gender, marital status, occupation, city type, and age group to understand their impact on purchase amounts.

## Machine Learning Models
1. **Linear Regression**: Modeled linear relationships between features and purchase amounts.
2. **Decision Tree Regression**: Captured non-linear patterns in the data.
3. **Random Forest Regression**: Utilized an ensemble of decision trees for improved accuracy.
4. **XGBoost**: Applied gradient boosting for robust predictions and better handling of complex patterns.

## Deep Learning Models
1. **1D CNN**: Convolutional Neural Network for regression to capture temporal dependencies.
2. **LSTM**: Long Short-Term Memory network to manage sequential data and dependencies.
3. **Feedforward Neural Network**: Standard neural network architecture for regression tasks.

## Performance Metrics
1. **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions.
2. **Mean Squared Error (MSE)**: Assesses the average of the squares of errors.
3. **Mean Absolute Percentage Error (MAPE)**: Evaluates the accuracy of predictions as a percentage.
4. **R² Score**: Indicates the proportion of variance in the target variable explained by the model.
