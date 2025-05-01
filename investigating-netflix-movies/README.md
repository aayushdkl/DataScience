# Netflix 1990s Movies Analysis

A data science project to analyze Netflix movie data from the 1990s, focusing on movie durations and the prevalence of short action movies, to inform nostalgic film production.

## Project Overview

This project explores Netflix movie data to understand the characteristics of films released in the 1990s. The analysis answers two key questions: what was the most frequent movie duration in the 1990s, and how many short action movies (less than 90 minutes) were released during this decade? The analysis is conducted using Python, pandas, and Jupyter Notebooks, with visualizations to provide context, all within a virtual environment for reproducibility.

**Author**: Aayush Dhakal  
**Date**: May 1, 2025

## Folder Structure

- `data/`
  - `raw/`: Contains the raw dataset (`netflix_data.csv`).
  - `processed/`: Stores cleaned datasets (empty for now).
- `notebooks/`: Jupyter Notebooks for analysis.
  - `notebook.ipynb`: Exploratory data analysis, including duration analysis and short action movie counts.
- `scripts/`: Python scripts for data processing (empty for now).
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file, describing the project.
- `redpopcorn.jpg`: Image used for visual context in the notebook or documentation.

## Dataset

The dataset (`netflix_data.csv`) contains information about Netflix shows and movies with the following columns:

- `show_id`: Unique ID of the show.
- `type`: Type of show (e.g., Movie, TV Show).
- `title`: Title of the show.
- `director`: Director of the show.
- `cast`: Cast of the show.
- `country`: Country of origin.
- `date_added`: Date added to Netflix.
- `release_year`: Year of release.
- `duration`: Duration of the show in minutes.
- `description`: Description of the show.
- `genre`: Genre of the show (e.g., Action, Comedy).

Located in `data/raw/netflix_data.csv`.
