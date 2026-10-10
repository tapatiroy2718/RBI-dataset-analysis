# RBI Weekly Dataset — Data Cleaning & Exploratory Analysis

## Contents
- `RBI_Weekly_Dataset_Analysis.ipynb` — original notebook, organized into inspection, cleaning, preprocessing, and exploratory-analysis phases.
- `RBI_Weekly_Dataset_Analysis.py` — Python-script export of the notebook code.
- `Week_1_Report.docx` — short report describing the workflow and deliverables.

## Dataset required
The notebook references the source file `tapatir630_17866381335214086.csv` (675 rows × 26 columns, as stated in the notebook). The CSV itself was not included with the uploaded notebook, so it is not bundled here and a cleaned CSV cannot be generated from the notebook alone.

Download the source dataset from the dataset location you used, then put `tapatir630_17866381335214086.csv` in the same folder as the `.py` file. In the notebook, update `RAW_PATH` to the local file path if necessary.

## Run
Install the main dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

Then run the notebook in Jupyter, or run:
```bash
python RBI_Weekly_Dataset_Analysis.py
```

The analysis exports `RBI_weekly_dataset_cleaned.csv` when the source CSV is available and the cleaning steps complete successfully.

## Main workflow
1. Inspect dataset dimensions, data types, missing values, and duplicate records.
2. Standardize column names and text values; parse dates and convert numeric fields.
3. Check invalid, missing, infinite, negative, and outlier values.
4. Apply time-series-oriented cleaning and derive date features / percentage-change variables.
5. Explore distributions, correlations, and time-based trends.

## Before submission
- Add the original source CSV if your assignment/repository requires it.
- Run the notebook/script and verify `RBI_weekly_dataset_cleaned.csv` is created.
- Add screenshots of key outputs/charts if required by your internship instructions.
