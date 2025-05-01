# Debugging a Sales Data Workflow

A data engineering project to troubleshoot and fix issues in the `load_and_check()` function, ensuring the sales data pipeline processes `sales.csv` correctly and returns two success messages.

## Project Overview

This project focuses on debugging a sales data workflow that has encountered issues after a recent update. The `load_and_check()` function, responsible for loading and validating the `sales.csv` dataset, is failing to perform as expected. The goal is to identify and resolve issues within the function, ensuring it verifies the dataset's shape, conducts integrity checks, and confirms the `Tax` column (5% of the subtotal, calculated as `Unit Price * Quantity`). The analysis is conducted using Python, pandas, and Jupyter Notebooks, with all fixes applied inside the function to maintain data integrity.

**Author**: Aayush Dhakal  
**Date**: May 1, 2025

## Folder Structure

- `data/`
  - `raw/`: Contains the raw dataset (`sales.csv`).
  - `processed/`: Stores cleaned datasets (empty for now).
- `notebooks/`: Jupyter Notebooks for analysis and debugging.
  - `debug_sales_workflow.ipynb`: Notebook for testing and debugging the `load_and_check()` function.
- `scripts/`: Python scripts for data processing.
  - `sales_pipeline.py`: Contains the `load_and_check()` function (to be debugged).
- `requirements.txt`: List of Python dependencies.
- `README.md`: This file, describing the project.
- `redpopcorn.jpg`: Image used for visual context in the notebook or documentation.

## Dataset

The dataset (`sales.csv`) contains sales data with the following key columns:

- `Total`: Total sale amount.
- `Quantity`: Number of units sold.
- `Unit price`: Price per unit.
- `Tax`: Tax amount (should be 5% of the subtotal, where subtotal = `Unit Price * Quantity`).
- `Date`: Date of the sale.

Located in `data/raw/sales.csv`.
