# CatBoost Regression for Perovskite Stability Prediction

## Overview
This project uses CatBoost regression to predict formation-energy-related perovskite stability from materials feature data. The workflow includes data preprocessing, training/validation/test splitting, model training, hyperparameter comparison, and performance visualization.

## Motivation
Perovskite stability is important for screening candidate materials in energy and electronic applications. Machine learning models can help identify structure-property trends and support faster materials discovery.

## Methods
- Python
- Pandas
- CatBoost regression
- Train/validation/test splitting
- RMSE-based model evaluation
- Hyperparameter comparison
- Data visualization with Matplotlib and Seaborn

## Results
The project compared CatBoost models with different depth, learning rate, iteration, and L2 regularization settings. Model performance was visualized using RMSE learning curves, predicted-vs-actual plots, and an overfitting landscape showing the relationship between iterations, L2 regularization, and train-validation RMSE gap.

## Skills Demonstrated
- Materials informatics
- Machine learning regression
- CatBoost model development
- Hyperparameter tuning
- Overfitting analysis
- Scientific data visualization

## Repository Structure
- `CatBoost Regression for Perovskite Stability Prediction.ipynb`: cleaned Jupyter notebook for the full modeling workflow
- `key_results/`: main result figures, including predicted-vs-actual plots, learning curves, and overfitting analysis

## Notes
This repository is a cleaned academic project summary. Large datasets, private course materials, and unnecessary temporary files are not included.
