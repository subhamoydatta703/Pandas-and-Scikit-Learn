# Scikit-Learn and Pandas Learning Repository

This repository contains educational materials and practice notebooks for learning data manipulation with Pandas and machine learning with Scikit-Learn.

## Project Structure

- `pandas/pandas_beginner.ipynb`: Introduction to Pandas DataFrames and Series. Covers data loading, exploration, and selection techniques.
- `sklearn/sklearn_day1.ipynb`: Introduction to Scikit-Learn. Covers Linear Regression, Decision Trees, Train/Test splitting, and Cross-Validation.
- `data/data_pandas_practice.csv`: Practice dataset used by the Pandas notebook.
- `requirements.txt`: Python dependencies for running the notebooks.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

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

Launch Jupyter Notebook to explore the tutorials:
```bash
jupyter notebook
```

Open each notebook from its library folder. The Pandas notebook reads its practice CSV from the repository's `data/` folder, so it does not depend on an absolute local path.

## Topics Covered

### Pandas
- Data loading from CSV
- DataFrame and Series structures
- Indexing and Slicing (`loc`, `iloc`)
- Basic statistics and data info

### Scikit-Learn
- Linear Regression for continuous predictions
- Decision Tree Classification
- Robust model evaluation using Cross-Validation
- Stratified sampling techniques
- Overfitting and Data Leakage prevention
