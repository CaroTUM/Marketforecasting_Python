# Marketforecasting_Python

## Overview

This repository contains a comprehensive machine learning pipeline designed to predict financial market response variables. Various regression models were explored, with a final focus on optimizing a LightGBM model enhanced through SHAP-based feature analysis and Bayesian hyperparameter tuning.

The relevant folders are data, models and notebooks. The detailed steps can be understood by reading the detailed project report. 

# Data

The raw data is a parquet format and contains the data of day0, which represent the relavant part of the data. The steps of the data cleaning can be tracked in the notebook datacleaning_finalcode.ipynb. The cleaned data set is saved in the data - raw folder. 

# Notebooks for model testing

The notebooks folder contains the code for the six models tested: Random Forest, Ridge, MLP, XGBoost, LassoRegression, and LightGBM. because the light gbm has been particularly well tested and improved, the code is distributed across three notebooks: LightGBM.ipynb for the baseline model, LightGBM_shap.ipynb for a SHAP analysis and related optimizations and LightGBM_optimization.ipynb for further optimizations, i.e. the Bayesian Optimization. 
