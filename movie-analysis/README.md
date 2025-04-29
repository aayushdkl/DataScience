# Movie Ratings Analysis

A data science project to explore a dataset of movie ratings, analyze trends, and visualize insights such as average ratings by genre and rating distribution.

## Project Overview

This project uses a small dataset of movie ratings to perform exploratory data analysis (EDA). It includes visualizations like bar charts and histograms to understand genre popularity and rating trends. The project is built using Python, Jupyter Notebooks, and a virtual environment for reproducibility.

**Author**: Ayush  
**Date**: April 29, 2025

## Folder Structure

- `data/`
  - `raw/`: Contains the raw dataset (`movies.csv`).
  - `processed/`: Stores cleaned datasets (e.g., `movies_cleaned.csv`).
- `notebooks/`: Jupyter Notebooks for analysis.
  - `01_eda.ipynb`: Exploratory data analysis with visualizations.
- `scripts/`: Python scripts for data processing.
  - `clean_data.py`: Script to clean the raw dataset.
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file, describing the project.

## Dataset

The dataset (`movies.csv`) is a small, custom CSV file with the following columns:

- `movie_id`: Unique ID for each movie.
- `title`: Movie title.
- `genre`: Movie genre (e.g., Animation, Action, Romance).
- `rating`: Average rating (0–5 scale).

Located in `data/raw/movies.csv`.
