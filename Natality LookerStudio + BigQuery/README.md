Project Link:
https://lookerstudio.google.com/s/o-Mt5WD_gKw




Project 1 — US Natality Analysis

BigQuery + Looker Studio

Problem

Analyze birth trends in the United States by geography and time, enabling interactive exploration by year, state, and county.

Data Source

Public CDC Natality data (BigQuery public datasets).

Data Modeling & Preparation

Normalized geographic fields using state codes for mapping consistency

Aggregated births at multiple grain levels (state, county, year)

Implemented dynamic Top-N ranking using SQL window functions

Built reconciliation queries to validate totals between raw and aggregated layers

Tools Used

BigQuery (SQL)

Looker Studio

Key Features

Interactive US map by state

Year-based and cross-chart filtering

Dynamic Top 5 states by births

Fully validated totals across views
