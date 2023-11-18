# MIE368-F1


## Overview

This project aims to predict Formula One race positions using Data Science and Machine Learning techniques. The dataset includes historical information about races, drivers, teams, circuits, and race results. The goal is to build a model that accurately predicts a driver's race position based on various features such as driver age, team, grid position, and more.

## Data Collection and EDA

### File Merging
We utilized the Formula One 1950-2023 dataset from Kaggle, merging eight CSV files containing information about circuits, teams, drivers, and race results.

### Feature Engineering
We performed feature engineering to create relevant features, including driver age, position delta, and driver Did Not Finish (DNF) ratio. This step enhanced our dataset for better prediction capabilities.

### EDA + Feature Selection
Exploratory Data Analysis (EDA) included visualizations of driver age distribution, relationships between age and wins, and DNFs by circuit. Feature selection involved correlation analysis to include relevant columns in the model.

## Feature Engineering

The following features were created during feature engineering:

- Driver Age
- Position Delta
- Driver DNF Ratio
- Binary features for race wins and podium finishes

## Model Development

We experimented with various machine learning models, including Random Forest, XGBoost, SVM, KNN, and Logistic Regression. The models were evaluated using accuracy metrics, and confusion matrices were plotted to assess performance.

## Next Steps

Our future steps include:

- Further model refinement using hyperparameter tuning and cross-validation.
- Integration of weather data to enhance feature space.
- Feature importance tests to avoid overfitting.
- Development of an optimization model for sports betting and fantasy league use cases.

## Getting Started

Follow these steps to get started with the project:

### Requirements

- Python (>=3.6)
- Required Python packages (install using `pip install -r requirements.txt`)

### Usage

1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter notebooks to explore the data, perform EDA, and build models.

## Contributing

Contributions are welcome! If you have ideas for improvement or find any issues, feel free to open an issue or create a pull request.
