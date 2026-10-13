# Volcano Data & SQL Analysis

A collection of Python exercises covering API extraction, data cleaning, exploratory analysis, and SQL queries.

## What it covers
- Retrieve eruption records from a public NOAA API and process them with **pandas**.
- Clean date columns and missing values, group events by country, and visualize eruption patterns.
- Query salary data using SQLite, including filtering, averages, and year-based tables.
- Use pandas groupby and aggregation for a smaller sales-data example.

## Files
- [`volcano-and-sql.ipynb`](volcano-and-sql.ipynb) — selected code cells organized by topic.
- [`volcanoes.csv`](volcanoes.csv) — saved sample volcanic eruption data.

## Run
From the repository root, install `requirements.txt` and open this notebook using Jupyter or VS Code. Running the first section calls the NOAA service, so it needs an internet connection. The included `volcanoes.csv` is an offline snapshot.

**SQL section:** The notebook expects `database.sqlite` with a `Salaries` table in its working directory. The original downloaded 35 MB database is not included. To run the SQL section, provide that external dataset locally. Without it, the NOAA and in-notebook grouping sections can still be read independently.

> Adapted from University of Maryland coursework. Prompts and instructional material were omitted; notebook cells reflect the coursework implementation.
