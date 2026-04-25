# Scikit-Learn and Pandas Learning Repository

This repository contains educational materials and practice notebooks for learning data manipulation with Pandas and machine learning with Scikit-Learn.

## Project Structure

- `pandas/pandas_beginner.ipynb`: Introduction to Pandas DataFrames and Series. Covers data loading, exploration, and selection techniques.
- `pandas/pandas_intermediate.ipynb`: Intermediate Pandas techniques. Covers data aggregation (`groupby`, `agg`), custom functions using `lambda`, and combining DataFrames (`merge`, `join`, `concat`).
- `pandas/pd_bg_prac1.ipynb`: Additional Pandas practice using a larger email dataset. Covers CSV loading, DataFrame inspection, column selection, and `loc`/`iloc` access.
- `sklearn/sklearn_day1.ipynb`: Introduction to Scikit-Learn. Covers Linear Regression, Decision Trees, Train/Test splitting, and Cross-Validation.
- `data/data_pandas_practice.csv`: Practice dataset used by the Pandas notebook.
- `data/emails.csv`: Optional larger email dataset expected by `pandas/pd_bg_prac1.ipynb`. Add this file locally if you want to run that notebook.
- `requirements.txt`: Python dependencies for running the notebooks.

## Getting Started

### Prerequisites

- Python 3.12 or another recent Python 3 version
- JupyterLab, installed from `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Launch JupyterLab to explore the notebooks:
```bash
jupyter lab
```

Open each notebook from its library folder.

- `pandas/pandas_beginner.ipynb` reads `data/data_pandas_practice.csv` from this repository.
- `pandas/pandas_intermediate.ipynb` uses small in-notebook data, so it does not need a separate dataset.
- `pandas/pd_bg_prac1.ipynb` reads `data/emails.csv`. Place the email dataset there before running the notebook.
- `sklearn/sklearn_day1.ipynb` uses small in-notebook NumPy arrays, so it does not need a separate dataset.

## Git Push Checklist

Before pushing to GitHub, check what changed:
```bash
git status
```

Stage and commit the updated project files:
```bash
git add README.md requirements.txt pandas/pd_bg_prac1.ipynb pandas/pandas_intermediate.ipynb
git commit -m "Update notebook paths and project docs"
```

Push your branch:
```bash
git push
```

If `data/emails.csv` is large or private, do not commit it. Keep it local and document where to download it instead.

## Topics Covered

### Pandas
- Data loading from CSV
- DataFrame and Series structures
- Indexing and Slicing (`loc`, `iloc`)
- Basic statistics and data info
- Working with NumPy scalar values inside Pandas
- Data Aggregation (`groupby`, `agg`)
- Custom calculations using `lambda` functions
- Combining DataFrames (`merge`, `join`, `concat`)

### Scikit-Learn
- Linear Regression for continuous predictions
- Decision Tree Classification
- Robust model evaluation using Cross-Validation
- Stratified sampling techniques
- Overfitting and Data Leakage prevention
