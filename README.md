# 🎓 Student Management System

A Python-based Student Management System developed as a PBL project. The project focuses on managing and analyzing student data using Python and data science techniques.

## Project Overview

The Student Management System is designed to work with student records and perform data analysis on the available student dataset.

The project uses Python-based data processing and analysis techniques to understand student information and academic performance.

## Features

- Student data management
- Student dataset handling using CSV
- Data preprocessing and analysis
- Analysis of student academic information
- Statistical analysis of student data
- Data visualization
- Student performance analysis
- Clustering of student data

## Student Data Analysis

The student dataset is processed and analyzed to identify useful patterns and relationships within the student records.

The analysis includes:

- Student academic performance
- Marks and other student attributes
- Data distribution
- Statistical analysis
- Visualization of student-related data

## Data Visualization

Data visualization is used to represent student information graphically and make patterns easier to understand.

The project uses graphs and charts to analyze and visualize the student dataset.

## Beyond Syllabus

### DBSCAN Clustering

**DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** is implemented as the Beyond Syllabus topic in the Student Management System.

DBSCAN is a density-based clustering algorithm that groups data points based on their density and identifies points that do not belong to any cluster as noise.

### DBSCAN in Student Management System

DBSCAN is applied to the student dataset to identify groups of students having similar characteristics based on the selected features.

It can help identify:

- Groups of students with similar characteristics
- Patterns within student data
- Different student clusters
- Students that may be considered outliers

### DBSCAN Parameters

DBSCAN mainly uses two parameters:

- **eps (ε):** The maximum distance between two points to be considered neighbors.
- **min_samples:** The minimum number of neighboring points required to form a dense region.

### DBSCAN Clustering Result

The generated clusters are analyzed and visualized to understand the groups identified within the student dataset.

Students belonging to the same cluster have similar characteristics according to the selected features, while noise points represent data points that do not belong to any particular cluster.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Files

| File | Description |
|---|---|
| `PDS_pbl.ipynb` | Main Student Management System project notebook |
| `students_dataset.csv` | Dataset used for student data analysis |
| `README.md` | Project documentation |

## Conclusion

The Student Management System demonstrates the use of Python and data science techniques for managing and analyzing student data.

The project includes data processing, analysis, visualization, and student performance analysis.

As a Beyond Syllabus enhancement, **DBSCAN clustering** is implemented within the Student Management System to identify groups and patterns in the student dataset.

The project provides practical experience in Python, data analysis, visualization, and machine learning techniques.
