# Data Science Projects

This repository contains a collection of my data science projects, each organized in its own subfolder. Each project includes datasets, Jupyter Notebooks, Python scripts, and documentation for exploratory data analysis (EDA), visualizations, and more. This portfolio showcases my skills in data manipulation, visualization, and analysis using Python.

**Author**: Aayush Dhakal
**Created**: April 29, 2025  
**GitHub**: [aayushdkl](https://github.com/aayushdkl)

---

## 📁 Projects

- **movie-analysis**: A project analyzing a dataset of movie ratings to explore genre trends and rating distributions using visualizations like bar charts and histograms.  
  ➤ See [`movie-analysis/README.md`](movie-analysis/README.md) for detailed insights and code walkthrough.
- **nyc-school-test-scores**: Analyzed standardized test performance data from NYC public schools to identify top-performing schools in math, rank the top 10 schools by combined SAT scores, and determine the borough with the largest standard deviation in SAT scores using pandas for data manipulation and summary statistics.  
  ➤ See [`nyc-school-test-scores/README.md`](nyc-school-test-scores/README.md) for detailed insights and code walkthrough.

---

## 🗂 Folder Structure

```plaintext
DataScience/
├── Project-Name/
│   ├── data/
│   │   ├── raw/            # Raw datasets (e.g., movies.csv)
│   │   └── processed/      # Cleaned datasets
│   ├── notebooks/          # Jupyter Notebooks for EDA and visualizations
│   ├── scripts/            # Python scripts for data processing
│   ├── requirements.txt    # Project-specific dependencies
│   └── README.md           # Project documentation
├── README.md               # Main portfolio README
```

---

## ⚙️ Setup Instructions

To run any project:

### 1. Clone the repository

```bash
git clone https://github.com/aayushdkl/jbooks.git
cd jbooks
```

### 2. Create a virtual environment

```bash
python -m venv ds-env
```

### 3. Activate the environment

- **Windows**:
  ```bash
  .\ds-env\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source ds-env/bin/activate
  ```

### 4. Navigate to a project folder

```bash
cd movie-analysis
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🧪 Running Notebooks or Scripts

- Open the project in **VS Code** or JupyterLab.
- Select the Python interpreter from the virtual environment (`ds-env`).
- For notebooks:  
  Open `notebooks/01_eda.ipynb` and run the cells.
- For scripts:  
  Right-click a `.py` file (e.g., `scripts/clean_data.py`) in VS Code and select **Run Python File in Terminal**.

---

## 📦 Common Dependencies

Dependencies may vary per project, but commonly include:

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` – Data visualization
- `seaborn` – Statistical plots
- `jupyter` – Notebook interface

Install each project's dependencies using the relevant `requirements.txt`.

---

## ⚠️ Notes

- The virtual environment (`ds-env`) is not included in this repository.
- Recreate it locally using the setup instructions above.
- If Jupyter Notebooks fail to run, make sure the kernel is available:

  ```bash
  pip install ipykernel
  python -m ipykernel install --user --name ds-env --display-name "Python (ds-env)"
  ```

---

## 🚧 Future Projects (Coming Soon)

- **Sales Analysis**: Retail data insights
- **Weather Trends**: Historical weather patterns
- **Social Media Analysis**: Sentiment detection on tweets or posts
- And more as I continue my data science journey...

---

## 🤝 Contributing

This is a personal portfolio, but suggestions and feedback are welcome.  
Feel free to [open an issue](https://github.com/aayushdkl/jbooks/issues) or connect via GitHub.

---

## 📄 License

This repository is licensed under the **MIT License**.  
See the [`LICENSE`](LICENSE) file for details.

---

**Happy exploring my data science journey! 🚀**
