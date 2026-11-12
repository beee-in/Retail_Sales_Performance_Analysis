# Retail Sales Performance Analysis

> **Portfolio staging copy — not yet a finished independent project.**
>
> Reference repository: https://github.com/saloniprasad017/Retail_Sales_Data_Analytics
> The original source is credited here. Obtain permission and review the source
> repository's license before republishing or adapting its code.

## Project objective
Analyze retail order data to understand sales trends, product/category performance,
regional patterns, customer segments, and shipping behavior.

## Current contents
- `scripts/data_cleaning.py` — baseline cleaning workflow from the reference project.
- `scripts/eda_analysis.py` — baseline exploratory analysis from the reference project.
- `scripts/kpi_analysis.py` — baseline KPI calculations from the reference project.
- `sql/sales_analysis.sql` — baseline SQL analysis from the reference project.
- `data/` — local data directories; datasets are excluded pending source/license review.
- `dashboard/` and `images/` — placeholders; no working dashboard was supplied.

## Known issues to resolve
- The supplied raw dataset has a `Sales` field but no `Profit` field. Profit queries
  and plots in the reference scripts therefore cannot run against that dataset.
- The supplied SQL uses some column names that do not match the CSV headers.
- The supplied dashboard image is invalid/empty and no PBIX file was provided.
- The original requirements file was empty.

## Planned work before presenting this as a portfolio project
- Verify dataset provenance and permitted redistribution.
- Correct and test all column names and SQL queries.
- Rebuild the analysis around metrics supported by the dataset, or source a
  properly licensed dataset with cost/profit fields.
- Create original visualizations and document verified findings.
- Add dependency versions and reproducible run instructions.

## Run status
This is an initial staging structure. It has not yet been validated end-to-end.
Do not describe planned work as completed work.
