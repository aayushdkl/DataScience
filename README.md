# NYC Public School Test Result Scores Analysis

A data science project to analyze standardized test performance data from NYC public schools, identify top-performing schools, and explore borough-level variations in SAT scores.

## Project Overview

This project uses a dataset of SAT scores from NYC public schools to perform exploratory data analysis (EDA) and answer key questions: which schools have the best math scores, what are the top 10 schools by combined SAT scores, and which borough has the largest standard deviation in SAT scores. The analysis is conducted using Python, pandas, and Jupyter Notebooks, with visualizations for context, all within a virtual environment for reproducibility.

**Author**: Ayush  
**Date**: April 30, 2025

## Folder Structure

- `data/`
  - `raw/`: Contains the raw dataset (`schools.csv`).
  - `processed/`: Stores cleaned datasets (empty for now).
- `notebooks/`: Jupyter Notebooks for analysis.
  - `notebook.ipynb`: Exploratory data analysis and main analysis (best math schools, top 10 schools, borough stats).
- `scripts/`: Python scripts for data processing (empty for now).
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file, describing the project.
- `schoolbus.jpg`: Image used for visual context in the notebook or documentation.

## Dataset

The dataset (`schools.csv`) contains SAT performance data for NYC public schools with the following columns:

- `school_name`: Name of the school.
- `borough`: NYC borough where the school is located (e.g., Manhattan, Brooklyn).
- `average_math`: Average SAT math score (out of 800).
- `average_reading`: Average SAT reading score (out of 800).
- `average_writing`: Average SAT writing score (out of 800).

Located in `data/raw/schools.csv`.
