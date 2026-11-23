# arXiv Preprints Analysis

**Stack:** Python · pandas · Jupyter

How do economics and software-engineering preprints differ?

## Analysis

Compare output and author counts by year, apply a title-based rule for machine learning, and examine publication indicators. Publication status inferred from available metadata is a proxy.

## Run locally

1. Install dependencies with `python -m pip install -r requirements.txt`.
2. Place your authorized input files at the paths referenced in the notebook. Expected inputs: `data/arxiv_econ_se.csv.gz`.
3. Open `analysis.ipynb` in Jupyter and run the cells from the repository root.

The input datasets and generated tables are excluded. The analysis requires inputs matching the original column schema.

Developed from STAT163 coursework at Kyiv School of Economics.
