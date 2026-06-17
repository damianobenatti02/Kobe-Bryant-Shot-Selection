# Kobe Bryant Shot Selection

## Project Objective
This repository contains the project based on the Kaggle competition [Kobe Bryant Shot Selection](https://www.kaggle.com/competitions/kobe-bryant-shot-selection).

The objective is to develop a machine learning model in Python to estimate the probability of Kobe Bryant making a shot by analyzing the spatial, temporal, and contextual characteristics of his throws over the course of his 20-year career.

## Repository Structure
* `/software`: Contains the Jupyter Notebook with data analysis, feature engineering, and model development, as well as the technical instructions to run the code.

## Results & Performance
During the model evaluation phase, two main algorithms were tested and compared: **XGBoost** and **Random Forest**. The performance difference between the two models on the Validation set was extremely tight (less than 1%). However, the **Random Forest Classifier** slightly outperformed XGBoost and was therefore selected as the final model for this project. 

When evaluated on the unseen Test set, the final Random Forest model achieved an **accuracy of over 67%**. This result demonstrates the model's solid capability to successfully capture the complex spatial, temporal, and contextual patterns behind Kobe Bryant's shot selection.