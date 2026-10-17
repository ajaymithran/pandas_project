![Pandas Projects banner](./pandas-project-banner.svg)

# Pandas Projects

> **A growing portfolio of data-cleaning, analysis, and visualization projects built with Python and pandas.**

---

Welcome! Each project explores a dataset, asks practical questions, and shares findings through clear analysis and visualizations. New pandas projects will be added here over time.

## Projects

### Coffee Shop Sales Analysis

Analyze coffee shop transactions to explore revenue by product category and store, daily sales patterns, and customer purchase quantities.

- [Open the analysis notebook](./coffee_sales_analysis/coffee-shop-pandas-analyis.ipynb)
- [Read the project details](./coffee_sales_analysis/README.md)
- Tools: Python, pandas, Matplotlib, Seaborn, Jupyter
- Main finding: Most transactions contain one or two items; coffee generated the most category revenue.

#### Run the coffee shop notebook

Install the required Python packages:

```bash
python -m pip install pandas matplotlib seaborn jupyter
```

Open the notebook in Jupyter or Visual Studio Code. The notebook expects its practice CSV in the same folder as the notebook. Data files are intentionally excluded from this repository; obtain the dataset separately and place the required CSV beside the notebook before running it.

#### Data and sharing

The source coffee shop dataset contains 149,116 transactions and 11 columns. The practice copy is modified for data-cleaning exercises. CSV files are excluded from version control; before sharing any dataset, confirm that its license permits redistribution and follow attribution requirements.

### Upcoming projects

More projects will be added here as they are completed. Use this format for future entries:

<!--
### Project name
A short description of the question or business problem.
- Notebook: [Open the analysis](./path/to/notebook.ipynb)
- Tools: Python, pandas, visualization libraries
- Key finding: One concise, evidence-based result.
-->

## Typical workflow

1. Load and inspect the data.
2. Check data types, missing values, and duplicates.
3. Clean and prepare the data.
4. Analyze trends and answer project questions.
5. Create visualizations and summarize evidence-based findings.
