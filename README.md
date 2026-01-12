## Project Overview

Description: Data cleaning pipeline for an employee dataset implemented as a Jupyter notebook. Dataset is extracted Kaggle, a large database with various datasets used for machine learning and other coding means. 

Link: https://www.kaggle.com/datasets/desolution01/messy-employee-dataset


## Files

Notebook: messy_data_cleaning.ipynb
Raw data: Messy_Employee_dataset.csv
Output: Cleaned_Employee_dataset.csv

## Dependencies

Python packages: pandas, numpy, matplotlib, seaborn, scikit-learn
Run environment: Jupyter Notebook / JupyterLab

## Usage

Open & run: Launch Jupyter and run messy_data_cleaning.ipynb.
Headless execution: jupyter nbconvert --to notebook --execute [messy_data_cleaning.ipynb](http://_vscodecontentref_/3) --output executed.ipynb

## Pipeline

Parsing: Parse Join_Date into year/month/day.
Normalization: Clean Phone, convert booleans, map Performance_Score.
Encoding: One-hot encode Status, Department and Region.
Imputation: Scale features, apply KNN imputer to Age and Salary, inverse-transform and post-process.
Save: Write cleaned data to Cleaned_Employee_dataset.csv.

## Notes

Warnings: Notebook suppresses warnings for cleaner output.
Adjustments: Update dataset path in the first cell if files are moved.
