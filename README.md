# A Machine Learning Approach to Study Li<sup>+</sup> Dynamics in Solid Polymer Electroltyes
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<h2 align="center">Currently under construction!🏗️👷🚧🛠️check back soon :)</h2>

This is the repository for my senior design project and thesis, titled "A Machine Leraning Approach to Study Li<sup>+</sup> Dynamics in Solid Polymer Electrolytes." Project was advised by Dr. Dmitry Bedrov and Aditya Choudhary from the University of Utah's Materials Science and Engineering Department.

## Exploratory Data Analysis

As the name implies, the notebook titled `exploratory_analysis.ipnyb` goes through the exploratory analysis of the data before the supervised learning tasks are performed. The notebook covers the following:
- Correlation heatmaps
- Distribution plotting (violin plots, histograms, KDEs)
- *K*-sample Anderson-Darling tests
- A UMAP embedding of the featurized data

## Full Machine Learnign Analysis

The notebook titled `full_analysis.ipynb` includes the code and explanations for the supervised learning tasks:

1. Use only structural features (coordination numbers) as features to predict Li<sup>+</sup> displacement
2. Use structural and dynamic features (changes in coordination number over a given timestep) to predict Li<sup>+</sup> displacement

Each task has a regression and classification approach.

## Feature Importances

More of an introduction to feature importances than anything else, `feature_importances.ipynb` has the code for the following:

- Impurity-based feature importance for tree-based models
- Permutation importance from scikit-learn
- SHAP feature importance

Explanations for this notebook are sparse, since feature importance really isn't useful for models with poor predictive ability.

## 3D Plotting

A short and sweet notebook adapted from a Plotly example for making some volume plots for one of my figures.
