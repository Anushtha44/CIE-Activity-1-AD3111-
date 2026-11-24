# CIE-Activity-1-AD3111-
# Stroke Prediction Dataset – Data Preparation

## Project Overview
This project focuses on inspecting, analyzing, cleaning, and preparing a healthcare dataset for future machine learning work. No prediction model was built.

## Objective
- Understand the structure of a tabular dataset.
- Identify missing values and data quality issues.
- Perform basic Exploratory Data Analysis (EDA).
- Handle missing values.
- Check duplicates and data consistency.
- Encode categorical variables.
- Scale numerical features.
- Save the cleaned dataset.

## Dataset
**Dataset:** Stroke Prediction Dataset

**Source:** [Kaggle – Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Preprocessing Performed
1. Dataset inspection using `head()`, `info()`, and `shape`.
2. Missing value analysis.
3. Median imputation for missing BMI values.
4. Duplicate row and ID checks.
5. Categorical consistency checks.
6. Numerical statistical analysis.
7. Exploratory Data Analysis using histograms, bar charts, and boxplots.
8. One-Hot Encoding of categorical columns.
9. Standardization of continuous numerical features using StandardScaler.
10. Final dataset verification.

## Missing Values
The BMI column contained 201 missing values (approximately 3.93%). These were filled using the median BMI of 28.1.

## Final Dataset
- **Rows:** 5,110
- **Columns:** 22
- **Missing values:** 0
- **Duplicate rows:** 0

## Output
`stroke_dataset_prepared.csv`

## Conclusion
The dataset was successfully cleaned and prepared for future machine learning analysis. Missing values were handled, categorical variables were encoded, continuous numerical features were scaled, and the final dataset was verified.

## Acknowledgement
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129
