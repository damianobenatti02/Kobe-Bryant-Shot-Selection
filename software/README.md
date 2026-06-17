# Software and Data - Kobe Bryant Shot Selection

## Dataset Reference
The data used comes from the official Kaggle competition: [Kobe Bryant Shot Selection](https://www.kaggle.com/c/kobe-bryant-shot-selection/data).

**Please note:** The original dataset contains rows with an empty target variable (which Kaggle used as the final test set). For this project, after dropping those rows from the `data.csv` file, the remaining dataset was split locally into Training, Validation, and Test sets to evaluate the model.

## Prerequisites
To run the Jupyter Notebook, you must install the following Python libraries:
* `pandas`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `seaborn`
* `xgboost`

## Startup Instructions
1. Download the `data.csv` file from Kaggle and place it in this exact directory (`/software`).
2. Open the `kobe_analysis.ipynb` file using Jupyter Notebook or VS Code.
3. Run the cells in sequential order (*Run All*).