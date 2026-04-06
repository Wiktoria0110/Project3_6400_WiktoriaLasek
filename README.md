# Keyword Network Analysis

## Project Description
Analyzes keyword co-occurrence patterns in academic articles to identify central research themes using network analysis.

## Dataset
Real keyword data from academic articles (`data/keywords_data.csv`). Each row represents one article with a title and up to 12 keywords.

## Installation & Usage
```
pip install -r requirements.txt
```
Then open and run `notebook.ipynb` in Jupyter.

## Key Results
- 248 unique keywords and 2,141 co-occurrence relationships
- Most central keyword: "organizational behavior" (degree: 166, strength: 265)
- Strongest pair: "organizational behavior" & "organizational effectiveness" (co-occurred 11 times)
- Full interpretation in `report.pdf`

## Repository Contents

| File/Folder | Description |
|---|---|
| `data/keywords_data.csv` | Raw dataset — do not modify |
| `notebook.ipynb` | Jupyter Notebook with all code, outputs, and commentary |
| `report.pdf` | Written report interpreting the results |
| `outputs/figures/` | Saved plots |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Files excluded from version control |
