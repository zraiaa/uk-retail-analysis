<<<<<<< HEAD
# UK Online Store — Sales Data Cleaning & Customer Segmentation

I took a real (and messy) sales dataset from a UK-based online gift shop and turned it into a clean, useful analysis. The dataset has 541,909 transactions from December 2010 to December 2011.

## What this project does

1. **Checks the data for problems** — missing values, duplicate rows, cancelled orders, weird entries that aren't real products (like postage or bank fees)
2. **Cleans it up** — with clear reasons for every decision, not just deleting things randomly
3. **Explores the data with charts** — sales over time, which countries buy the most, best-selling products, when people place orders
4. **Groups customers by value** — using a method called RFM (Recency, Frequency, Monetary) plus a machine learning technique called K-Means, to find out which customers matter most
5. **Sums up what I found**, in plain language, backed by real numbers

## Main findings

- Sales rise steadily before Christmas, peaking in November
- 85% of all revenue comes from the UK — everything else is small in comparison
- The most popular products by revenue aren't the same as the most popular by quantity sold
- Orders only happen on weekdays — there were **zero** orders on any Saturday
- Just 13% of customers ("Champions") bring in 63% of all revenue

## Tools I used

- Python
- pandas (cleaning and analyzing data)
- matplotlib & seaborn (charts)
- scikit-learn (K-Means clustering)
- Jupyter Notebook

## Files in this repo

- `retail_analysis.ipynb` — the full notebook, with all the code, charts, and explanations
- `online_retail.csv` — the raw data used in this project
- `README.md` — this file

## How to run it yourself

1. Install the tools needed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
2. Open the notebook:
```bash
jupyter notebook retail_analysis.ipynb
```
3. Run all the cells from top to bottom

## Where the data came from

This dataset is the **Online Retail Dataset** from the UCI Machine Learning Repository, shared under a Creative Commons license.
Source: https://archive.ics.uci.edu/dataset/352/online+retail

## About me

This project was built as part of my personal portfolio to practice and show my data cleaning, analysis, and machine learning skills.
=======
# uk-retail-analysis
Cleaned and analyzed 540K+ transactions from a UK online retailer — EDA on sales trends, geography, and product performance, plus RFM + K-Means customer segmentation to identify top-value customers.
>>>>>>> eacbdfc25b9c3a24041a58baf4f7471f6c41233e
