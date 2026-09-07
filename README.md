# California Housing EDA

This project explores the California Housing dataset through visualization and predictive modeling.

## Objectives

- Understand the structure and distribution of the housing data
- Compare global linear regression with local kNN regression
- Study the effect of squared and absolute loss
- Examine how increasing dimensionality affects nearest-neighbor geometry
- Compare OLS with Ridge and Lasso regularization

## Dataset

The project uses the California Housing dataset from `sklearn.datasets`.

Features include:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target:

- Median House Value

## Methods Used

- Exploratory Data Analysis
- Linear Regression
- k-Nearest Neighbors Regression
- Squared Loss
- Absolute Loss
- Nearest-Neighbor Distance Analysis
- Ridge Regression
- Lasso Regression
- Cross-Validation

## Repository Structure

```text
.
├── california_housing_eda.ipynb
├── figs/
│   ├── 01_house_value_distribution.png
│   ├── ...
│   └── 11_regularization_cv.png
├── report.pdf
└── README.md
