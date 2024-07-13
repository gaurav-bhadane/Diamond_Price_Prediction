# Diamond Price Prediction

This Project aims to Predict Diamond Prices using various regression algorithms. It involves data preprocessing, feature engineering, and applying different regression models to find the best predictor.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Diamond pricing can be complex as it depends on multiple factors such as carat, cut, color, clarity, and more. This project leverages various regression algorithms to predict the price of diamonds based on these features.

## Dataset
The dataset used for this project can be found on [Kaggle](https://www.kaggle.com/shivam2503/diamonds). It contains the following features:
- `carat`: The weight of the diamond.
- `cut`: The quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- `color`: The diamond color, from J (worst) to D (best).
- `clarity`: A measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)).
- `depth`: The depth percentage.
- `table`: The width of the top of the diamond relative to the widest point.
- `price`: The price of the diamond.
- `x`: Length in mm.
- `y`: Width in mm.
- `z`: Depth in mm.

## Requirements
To run this project, you will need the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Installation
1. Clone the repository: `git clone https://github.com/gaurav-bhadane/Diamond_Price_Prediction.git`
2. Navigate to the project directory: `cd diamond-price-prediction`
3. Install the required packages: `pip install -r requirements.txt`

## Usage
1. Start a Jupyter notebook: `jupyter notebook`

## Models Used
The following regression models were used in this project:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression
4. Gradient Boosting Regression
5. Support Vector Regression (SVR)

## Evaluation
The models are evaluated using the following metrics:

1. Mean Absolute Error (MAE)
2.Mean Squared Error (MSE)
3. Root Mean Squared Error (RMSE)
4. R-squared (R²)

## Results
The performance of each model is summarized in the notebook. Based on the evaluation metrics, the model with the best performance is chosen.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
