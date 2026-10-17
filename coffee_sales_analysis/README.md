# Coffee Shop Sales Analysis with Pandas

This project uses pandas to clean coffee shop transaction data, analyze sales performance, and create charts for business questions.

## Project structure

- `coffee-shop-pandas-analyis.ipynb` — cleaning exercise, analysis, and visualizations.
- `company_required_questions.txt` — analysis and plotting questions.
- `data/Coffee Shop Sales.csv` — original dataset used for business analysis (149,116 rows, 11 columns).
- `Coffee Shop Sales - pandas practice .csv` — intentionally modified copy for practicing missing-value, duplicate, and datatype cleanup.
- `.gitignore` — keeps local CSV datasets out of version control.

The notebook first cleans the practice copy, then reloads the original dataset for its business analysis so the intentional practice issues do not affect business conclusions.

## Data and sharing

The CSV files are local inputs and are excluded from version control. They are not included for redistribution. Before sharing or publishing either dataset, confirm that its source license permits redistribution and follow any attribution requirements. To run the notebook, obtain the files separately and place them at the paths shown above.

## Setup and run

From the project folder, install the required packages:

```bash
python -m pip install pandas matplotlib seaborn jupyter
```

Open `coffee-shop-pandas-analyis.ipynb` in Jupyter or Visual Studio Code and run the cells from top to bottom. Run it with the project folder as the working directory so the relative CSV paths resolve.

## Analysis and charts

The notebook calculates revenue as `transaction_qty * unit_price` and examines product category and store sales, daily revenue, transaction counts, transaction quantity distribution, and relationships between numeric measures.

In the original dataset, quantity 1 is the most common transaction size (87,159 transactions, 58.45%), and about 97.78% of transactions contain 1 or 2 items. The relationship between unit price and quantity is weakly negative (correlation about -0.12); this is an association, not evidence that price causes customers to buy less. Bundles or add-on offers could be tested and evaluated against actual sales results.
