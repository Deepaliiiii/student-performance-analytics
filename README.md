# Student Performance Analytics System

## Python with AI Mini Project

### Project Overview

The Student Performance Analytics System is a Python-based data analysis
project that analyzes student academic performance using Pandas and NumPy.

The system processes student marks and attendance data and generates useful
information such as total marks, average marks, grades, pass/fail status,
subject-wise performance, class performance, and top-performing students.

## Objective

The main objective of this project is to demonstrate the practical use of
Python programming, NumPy, Pandas, functions, loops, conditions, and data
analysis techniques to analyze student performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

## Dataset

The project uses a custom dataset containing 30 student records.

The dataset contains the following fields:

- Student ID
- Name
- Department
- Python Marks
- Mathematics Marks
- DBMS Marks
- AI Marks
- Attendance

## Project Features

- Load student data using Pandas DataFrame
- Calculate total marks
- Calculate average marks
- Assign grades
- Determine pass/fail status
- Calculate highest and lowest performance
- Calculate overall class average
- Perform subject-wise performance analysis
- Identify the best-performing subject
- Identify top 5 performing students
- Calculate pass/fail statistics
- Create data visualizations

## Grading Rule

| Average Marks | Grade |
|---|---|
| 90 - 100 | A+ |
| 80 - 89.99 | A |
| 70 - 79.99 | B |
| 60 - 69.99 | C |
| 50 - 59.99 | D |
| Below 50 | F |

## Pass/Fail Rule

A student is considered to have passed when:

- Average marks are at least 40
- Attendance is at least 75%

Students who do not satisfy both conditions are classified as Fail.

## Analysis Performed

The project answers practical questions such as:

- Which student has the highest average?
- Which student has the lowest average?
- Which subject has the highest average?
- How many students passed?
- How many students failed?
- What is the overall class average?
- Who are the top-performing students?

## Visualizations

The project includes:

1. Average Marks by Subject
2. Top 5 Students by Average Marks
3. Pass/Fail Distribution
4. Attendance vs Average Marks

## Project Files

```text
student-performance-analytics/
│
├── Student_Performance_Analytics.ipynb
├── students.csv
└── README.md
