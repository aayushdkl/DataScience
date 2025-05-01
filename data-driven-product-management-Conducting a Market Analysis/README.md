# Data-Driven Product Management: Conducting a Market Analysis

A data science project to analyze Google Trends data on fitness-related keyword searches to assess demand for digital fitness classes and identify growth opportunities for a fitness studio's digital products.

## Project Overview

As a product manager for a fitness studio, this project aims to conduct a market analysis to understand the demand for digital fitness classes. Using Google Trends data on fitness-related keywords (e.g., 'workout', 'home workout', 'gym workout', 'home gym'), the analysis explores global and country-level search trends to identify patterns and opportunities for digital product development. The analysis is conducted using Python, pandas, and Jupyter Notebooks, with visualizations to provide insights, all within a virtual environment for reproducibility.

**Author**: Aayush Dhakal  
**Date**: May 2, 2025

## Folder Structure

- `data/`
  - `raw/`: Contains the raw datasets (`workout.csv`, `three_keywords.csv`, `workout_geo.csv`, `three_keywords_geo.csv`).
  - `processed/`: Stores cleaned datasets (empty for now).
- `notebooks/`: Jupyter Notebooks for analysis.
  - `notebook.ipynb`: Exploratory data analysis and market trend visualizations.
- `scripts/`: Python scripts for data processing (empty for now).
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file, describing the project.
- `gym.jpg`: Image used for visual context in the notebook or documentation.

## Datasets

The project uses four CSV files containing Google Trends data, located in `data/raw/`:

1. **workout.csv**

   - `month`: Month when the data was measured.
   - `workout_worldwide`: Index (0–100) representing the popularity of the keyword 'workout'.

2. **three_keywords.csv**

   - `month`: Month when the data was measured.
   - `home_workout_worldwide`: Index (0–100) for the keyword 'home workout'.
   - `gym_workout_worldwide`: Index (0–100) for the keyword 'gym workout'.
   - `home_gym_worldwide`: Index (0–100) for the keyword 'home gym'.

3. **workout_geo.csv**

   - `country`: Country where the data was measured.
   - `workout_2018_2023`: Index (0–100) for the keyword 'workout' over 2018–2023.

4. **three_keywords_geo.csv**
   - `country`: Country where the data was measured.
   - `home_workout_2018_2023`: Index (0–100) for 'home workout' over 2018–2023.
   - `gym_workout_2018_2023`: Index (0–100) for 'gym workout' over 2018–2023.
   - `home_gym_2018_2023`: Index (0–100) for 'home gym' over 2018–2023.

Located in `data/raw/`.
