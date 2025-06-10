# Tikibook Data Analysis

This repository contains a Jupyter notebook for exploring book sales data from the Tiki e-commerce platform.

## Contents

- `Tiki Analyst.ipynb` – main notebook with analysis and visualizations.
- `Tiki Eng.pdf` / `Tiki Vie.pdf` – slides describing the project in English and Vietnamese.

## Requirements

The notebook requires Python 3 with the following packages:

- pandas
- numpy
- matplotlib
- seaborn
- dataprep

You can install them using `pip`:

```bash
pip install pandas numpy matplotlib seaborn dataprep
```

## Dataset

The analysis expects a file named `book_data.csv` in the project root. This dataset is not included in the repository. Place the CSV in the same directory as the notebook before running it.

If the file is missing, the notebook will raise a `FileNotFoundError` with instructions for obtaining the dataset.

## Usage

Open the notebook with Jupyter and run through the cells:

```bash
jupyter notebook "Tiki Analyst.ipynb"
```

## Tests

No automated tests are provided yet. After adding a test suite, run it with `pytest`:

```bash
pytest -q
```
