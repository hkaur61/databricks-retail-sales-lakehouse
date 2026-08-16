# databricks-retail-sales-lakehouse
End-to-end Databricks Lakehouse project using PySpark, Delta Lake, Medallion Architecture and Databricks SQL.
# Retail Sales Lakehouse - Databricks

## Overview

This project demonstrates an end-to-end data engineering solution
using Databricks, PySpark, Delta Lake and Databricks SQL.

The project implements a Medallion Architecture consisting of
Bronze, Silver and Gold layers.

## Architecture

CSV
 |
 v
Bronze
 |
 v
Silver
 |
 v
Gold
 |
 v
Databricks SQL
 |
 v
Dashboard

## Technologies

- Databricks
- PySpark
- Python
- SQL
- Delta Lake
- Databricks SQL
- Git
- GitHub

## Data Layers

### Bronze

Raw source data is ingested into Delta tables.

### Silver

Data is cleaned, validated and enriched.

### Gold

Business-ready dimensional and aggregated datasets are created.

## Data Quality

The project performs checks for:

- Duplicate orders
- Null customer IDs
- Invalid quantities
- Invalid dates

## Business KPIs

The solution provides:

- Total revenue
- Total orders
- Units sold
- Revenue by category
- Revenue by state
- Daily sales trends