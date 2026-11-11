# Student Performance Analysis

Exploratory analysis of the Kaggle dataset **Student Performance Factors**:
https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

The project covers score distributions, attendance patterns, sampling differences,
and the relationship between study habits and exam results.

## Contents
- `notebook.ipynb`: full analysis (statistical summary, 6 charts, sampling differences, correlation analysis, why correlation does not prove causation, five written insights)
- `spreadsheet_check.png`: Google Sheets cross-check of the mean, median, standard deviation and correlations

## How to run
1. Download the CSV from the Kaggle link above.
2. Upload `notebook.ipynb` and the CSV to Google Colab, then choose Runtime > Run all.
3. Or run locally: `pip install pandas matplotlib seaborn jupyter`, then `jupyter notebook`, and open `notebook.ipynb` (keep the CSV in the same folder).

## Key findings
- Mean exam score is about 67.24 (median 67, standard deviation about 3.89).
- Hours studied and exam score have a correlation of about 0.45.
- Attendance and exam score have a correlation of about 0.58, the stronger of the two.
- Small samples (n=10) vary widely from the true mean; larger samples (n=500) stay close to it.
- These are correlations, not proof of cause.

## Author
Azubuko Uju Scholastica
