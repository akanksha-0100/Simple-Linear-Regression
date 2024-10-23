
# Simple Linear Regression on Real Estate Prices
This project demonstrates how to apply a **simple linear regression** model to predict real estate prices based on property size. It is a part of an exercise that helps in understanding the basics of linear regression.

## Dataset
The dataset used is `real_estate_price_size.csv`, which contains two key variables:
- **Price** (Dependent variable): The price of a property.
- **Size** (Independent variable): The size of the property (in square meters).

## Project Overview
The project follows these steps:

1. **Importing Libraries**: Essential Python libraries such as `numpy`, `pandas`, `matplotlib`, and `statsmodels` are used for data handling, visualization, and model building.
   
2. **Loading the Dataset**: The dataset is read from a CSV file (`real_estate_price_size.csv`) into a pandas DataFrame for further analysis.

3. **Exploratory Data Analysis**: Basic exploratory analysis of the data, including summary statistics and visualizations, to understand the relationship between size and price.

4. **Building the Regression Model**: A simple linear regression model is created using the size of the property as the predictor and the price as the target variable.

5. **Evaluating the Model**: The model's performance is evaluated using standard metrics such as R-squared, coefficients, and plotting the regression line.

## Running the Project

1. Download or clone the repository.
2. Make sure you have the dataset `real_estate_price_size.csv` in the same directory as the notebook.
3. Open the Jupyter notebook (`Real_Estate_SimpleLinearRegression.ipynb`) and run all the cells.

## Results

The project builds a simple linear regression model to estimate the relationship between the size of a real estate property and its price. The final output includes:

- Visualization of the data points and the fitted regression line.
- Model summary showing the R-squared value and coefficients.

## Conclusion

This project provides a straightforward example of how linear regression can be applied to real estate pricing. The simplicity of the model makes it a good starting point for learning regression analysis.


