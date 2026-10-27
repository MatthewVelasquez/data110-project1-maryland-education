# Does Spending More per Student Mean More College Graduates?

DATA 110 Project 1 (Matthew Velasquez): a look at Maryland's 23 counties and Baltimore City
using the Choose Maryland "Compare Counties: Education" dataset.

**Main findings**
- Spending per student and bachelor's attainment are almost unrelated (r = 0.07).
- Spending follows class size (student-teacher ratio vs. spending, r = -0.58).
- Howard (61.4%) and Montgomery (59.0%) are far ahead on bachelor's attainment.

## How to run
Open the notebooks from their folders and run all cells, in this order:
1. `ingestion/notebooks/1.0-initial-data-cleaning.ipynb` cleans `data/raw/` into `data/processed/`
2. `eda/notebooks/1.1-eda-summary.ipynb` summarizes the data and makes the charts

Needs `pandas`, `numpy`, and `matplotlib`.

## Folders
- `data/raw/` original CSV (never modified); `data/processed/` cleaned table
- `ingestion/notebooks/` cleaning code
- `eda/notebooks/` summary statistics and charts; `eda/images/` charts
- `reports/final/` final report and slides (PDF); `reports/figures/` charts used in them
- `docs/sources/` where the data comes from
