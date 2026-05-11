# Student_Data_Processing

## Student Data Analysis

## Overview

This project focuses on processing and analyzing student academic performance data using Python and Pandas.

The notebook demonstrates essential data science workflows including data loading, preprocessing, filtering, transformation, feature engineering, statistical aggregation, duplicate handling, and exploratory data analysis (EDA).

The objective is to analyze student academic performance and extract meaningful insights from demographic and educational variables while applying professional data manipulation techniques.

---

## Dataset

The project uses the `student-mat.csv` dataset from the UCI Machine Learning Repository.

The dataset contains information related to:
- Student demographics
- Academic performance
- Educational and social attributes
- Grades from multiple evaluation periods

Main variables used in the analysis include:

- `school`: student's school
- `sex`: student's gender
- `age`: student's age
- `activities`: extracurricular activities
- `G1`, `G2`, `G3`: grades from three evaluation periods

---

## Main Tasks Performed

- Loading and inspecting datasets
- Filtering underage students
- Renaming and selecting relevant columns
- Creating pass/fail indicators
- Calculating average grades
- Grouping and aggregating data
- Statistical analysis by age and gender
- Identifying and removing duplicate rows

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure

```text
Student_Data_Processing/
│
├── data/
│   └── student-mat.csv
│
├── notebooks/
│   ├── student_data_analysis_english.ipynb
│   └── student_data_analysis_spanish.ipynb
│
├── README.md
└── requirements.txt
