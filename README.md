# Data Cleaning & Visualization Project

## Overview

This project demonstrates the complete data preprocessing and visualization workflow using Python. The objective is to clean a raw dataset, handle data quality issues, and generate meaningful insights through visualizations.

## Project Objectives

* Identify and handle missing values
* Detect and remove duplicate records
* Detect and handle outliers
* Perform exploratory data analysis (EDA)
* Create visualizations to uncover insights
* Generate a cleaned dataset for further analysis

## Dataset Information

The dataset contains employee information with the following attributes:

| Column     | Description         |
| ---------- | ------------------- |
| ID         | Employee ID         |
| Name       | Employee Name       |
| Age        | Employee Age        |
| Gender     | Gender              |
| Department | Department Name     |
| Salary     | Employee Salary     |
| Experience | Years of Experience |
| City       | Employee City       |

### Initial Dataset Summary

* Total Records: 25
* Total Columns: 8
* Missing Values:

  * Age: 1
  * Salary: 1
* Duplicate Records: Present
* Outliers: Present in Salary and Experience columns

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Data Cleaning Process

### 1. Missing Value Handling

* Identified missing values using Pandas.
* Filled or removed missing entries appropriately.

### 2. Duplicate Removal

* Checked for duplicate records.
* Removed duplicate rows to maintain data quality.

### 3. Outlier Detection

* Used the Interquartile Range (IQR) method.
* Visualized outliers using boxplots.
* Removed extreme values affecting analysis.

## Data Visualizations

The following visualizations were created:

### Salary Distribution

Histogram showing employee salary distribution.

### Department-wise Employee Count

Bar chart showing the number of employees in each department.

### Gender Distribution

Pie chart showing male and female employee proportions.

### Correlation Heatmap

Heatmap illustrating relationships among numerical features.

## Key Findings

* The dataset contained missing values in Age and Salary columns.
* Duplicate records were successfully identified and removed.
* Salary showed significant variation across employees.
* The Management department contained the highest salary values.
* Most employees belonged to IT, HR, and Finance departments.
* Experience and Salary showed a positive relationship.

## Project Structure

Data-Cleaning-Visualization-Project/

├── dataset.csv

├── cleaned_dataset.csv

├── data_cleaning.ipynb

├── README.md

└── visualizations/

    ├── histogram.png

    ├── bar_chart.png

    ├── pie_chart.png

    └── heatmap.png

## Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Data cleaning techniques
* Exploratory Data Analysis (EDA)
* Data visualization
* Data storytelling
* Python-based data analysis

## Author

Subrat Kumar Sahoo

B.Tech Computer Science & Engineering

Data Science Internship Project
