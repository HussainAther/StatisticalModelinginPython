# Red Wine Quality Prediction: Regression Analysis

## Project Overview

This project focuses on using regression analysis to predict alcohol levels in wine, leveraging a popular dataset available on Kaggle. Through exploratory data analysis (EDA), visualization, and the implementation of various regression models, we aim to predict the alcohol content in red wine with the highest accuracy possible.

## Dataset

The dataset used in this project, `wineQualityReds.csv`, is freely available on [Kaggle](https://www.kaggle.com/piyushgoyal443/red-wine-dataset). It contains physicochemical properties of red wine and its quality rating.

## Prerequisites

To run the analysis presented in this project, the following Python libraries are required:

- NumPy
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn

Ensure you have these libraries installed before proceeding. If not, you can install them using pip:

```sh
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
```

## Structure

The project is structured as follows:

1. **Sourcing and Loading**
   - Import relevant libraries
   - Load the data
   - Explore the data
   - Choose a dependent variable

2. **Cleaning, Transforming, and Visualizing**
   - Visualize correlations

3. **Modeling**
   - Train/Test split
   - Create and evaluate several linear regression models

4. **Evaluating and Concluding**
   - Reflect on the model's performance
   - Discuss the best model and other potential regression algorithms

## Key Findings

- Through EDA and correlation analysis, we chose 'fixed acidity' as our dependent variable, considering its relevance and continuous nature.
- Several regression models were built and evaluated, from simple linear regression to multiple linear regression models.
- Our analysis demonstrated the importance of including multiple predictors to improve model accuracy.
- The project highlights a balance between model complexity and interpretability, with a detailed exploration of model performance metrics like R-squared and RMSE.

## Usage

To replicate this analysis or explore the dataset further:

1. Clone this repository to your local machine.
2. Ensure all prerequisite libraries are installed.
3. Run the Jupyter notebooks to explore the dataset and regression models.

## Contributing

Contributions to enhance the analysis or explore other predictive models are welcome. Please feel free to fork this repository and submit your pull requests.

## License

This project is open-source and available under the MIT License.

