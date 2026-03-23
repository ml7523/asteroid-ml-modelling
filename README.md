# Asteroid ML Modelling

A machine learning project for asteroid diameter prediction and classification using astronomical observation data.

## Overview
This project explores supervised learning methods for:
- asteroid diameter regression
- asteroid class classification

The workflow includes feature selection, model comparison, nonlinear regression, and performance evaluation.

## Dataset
The dataset contains asteroid observation features such as:
- absolute magnitude
- albedo
- number of observations
- observation arc length
- orbital eccentricity
- orbital inclination
- orbital period

## Methods
Implemented methods include:
- Non-negative Garrote
- LASSO
- Kernel Ridge Regression
- Multilayer Perceptron (MLP)
- Cross-validation
- Bootstrap-based stability analysis

## Results
- Improved regression performance to approximately $$R^2 \approx 0.95$$ using a polynomial-kernel KRR model.
- Improved small-asteroid classification accuracy from 93.75% to 95.63%.

## Repository Structure
- `notebook.ipynb`: end-to-end analysis
- `figures/`: plots and visualisations
- `results/`: summary outputs

## Notes
This repository is a cleaned and project-based adaptation of academic coursework.
