# Data Preprocessing and Normalization using Python

## Overview

This project focuses on data preprocessing and normalization techniques used in machine learning and data analysis. The workflow includes data cleaning, handling missing values, treating outliers, and applying normalization methods to prepare the dataset for further analysis and modeling.

## Objectives

* Clean and preprocess raw data.
* Handle missing values and duplicate records.
* Detect and treat outliers.
* Apply Min-Max Scaling and Standardization.
* Compare data distributions before and after normalization.
* Prepare the dataset for machine learning algorithms.

## Data Cleaning

The following preprocessing steps were performed:

* Removal of duplicate records.
* Handling of missing values.
* Correction of inconsistent data formats.
* Identification and treatment of outliers.
* Selection of relevant numerical features for normalization.

## Normalization Techniques

### 1. Min-Max Scaling

Min-Max Scaling transforms data into a fixed range, typically between 0 and 1.

**Formula:**

X_scaled = (X - X_min) / (X_max - X_min)

### 2. Standardization (Z-Score Normalization)

Standardization transforms features to have a mean of 0 and a standard deviation of 1.

**Formula:**

Z = (X - μ) / σ

## Workflow

1. Load dataset.
2. Perform data cleaning.
3. Handle missing values.
4. Detect and treat outliers.
5. Apply Min-Max Scaling.
6. Apply Standardization.
7. Visualize and compare results.
8. Save the processed dataset.

## Results

The preprocessing pipeline improved data quality and reduced the impact of missing values and outliers. Both normalization methods successfully scaled the numerical features, making the dataset more suitable for machine learning models.

## Conclusion

Data cleaning and normalization are essential preprocessing steps that improve data quality and model performance. The project demonstrates the implementation and comparison of Min-Max Scaling and Standardization using Python.

## Author

Irene Bae
