# Task 30 — Exploratory Data Analysis Using Python


## Project Overview

This project demonstrates Exploratory Data Analysis (EDA) using Python, Pandas, NumPy, and Matplotlib.

A student performance dataset containing academic information is analyzed to understand data structure, identify data-quality issues, calculate descriptive statistics, and visualize meaningful patterns.

The project combines data exploration, cleaning, statistical analysis, and visualization into one complete EDA workflow.

## Objectives

- Understand the structure of a dataset.
- Inspect columns, data types, and records.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Calculate descriptive statistical measures.
- Create at least four meaningful visualizations.
- Analyze relationships between numerical variables.
- Identify at least five observations supported by data.
- Export the cleaned dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## Dataset Description

The project uses a manually created student performance dataset containing 30 unique student records.

The dataset includes six columns:

| Column | Description |
|---|---|
| student_id | Unique student identifier |
| gender | Student gender category |
| department | Academic department |
| study_hours | Hours spent studying |
| attendance_pct | Attendance percentage |
| marks | Examination marks |

The original dataset contains one duplicate record and four missing cells.

All records are fictional and created for educational purposes.

## Data Cleaning

The following operations were performed:

1. Identified one duplicate student record.
2. Removed the duplicate using Pandas `drop_duplicates()`.
3. Identified four missing cells.
4. Replaced missing numerical values using median imputation.
5. Represented the missing department using the `Unknown` category.
6. Verified that the cleaned dataset contains zero missing cells and zero duplicate student IDs.

## Statistical Analysis

The following statistical measures were calculated:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

## Visualizations

The project contains five visualizations:

### 1. Histogram of Student Marks

Displays the distribution and concentration of examination marks.

### 2. Average Marks by Department

Compares academic performance across CSE, ECE, and IT departments.

### 3. Study Hours vs Examination Marks

Uses a scatter plot and trend line to visualize the relationship between study hours and examination marks.

### 4. Department-wise Marks Box Plot

Compares the median and spread of examination marks across departments.

### 5. Correlation Heatmap

Shows the correlations among study hours, attendance, and examination marks.

## Key Findings

- Original records: 31.
- Duplicate records removed: 1.
- Final cleaned records: 30.
- Missing cells after treatment: 0.
- Average examination marks: 72.83.
- Average attendance: 85.77%.
- IT has the highest department average at 78.10.
- Study hours and marks have a correlation of approximately 0.9256.
- Attendance and marks have a correlation of approximately 0.9320.

## Project Files

- `Task_30_Exploratory_Data_Analysis.ipynb` — Complete EDA notebook.
- `student_performance_raw.csv` — Original dataset.
- `student_performance_cleaned.csv` — Cleaned dataset.
- `department_summary.csv` — Department-wise performance summary.
- `correlation_matrix.csv` — Correlation matrix.
- `eda_summary.csv` — Overall EDA summary.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.

### Charts

- `charts/marks_distribution.png`
- `charts/average_marks_by_department.png`
- `charts/study_hours_vs_marks.png`
- `charts/marks_by_department_boxplot.png`
- `charts/correlation_heatmap.png`

## Conclusion

This project demonstrates a complete basic EDA workflow using Python.

It combines dataset exploration, data cleaning, descriptive statistics, visualization, and observation generation to understand student performance data.

The project provides practical experience in preparing and analyzing structured data before applying machine-learning techniques.
