# Operations KPI Dashboard for a Fulfillment Center

## Overview

This project builds a small data warehouse and KPI layer for a retail / e-commerce operation using the Sample Superstore dataset. The goal is to design a star schema, write SQL to calculate core operational KPIs, and connect those tables to a Power BI dashboard.

## Data Source

- **Dataset:** Tableau Sample Superstore (Excel)
- **Fields include:** Order Date, Ship Date, Ship Mode, Region, Category, Sales, Profit, Quantity, etc.

The raw dataset is stored locally in `data/raw/` and not committed to this repository.

## Planned Deliverables

- Star schema with:
  - `fact_orders`
  - `dim_date`, `dim_customer`, `dim_product`, `dim_region`, `dim_ship_mode`
- SQL queries for:
  - Throughput
  - Backlog / open orders
  - Processing time (order → ship)
  - Inventory / category-level KPIs
  - 7-day rolling KPIs using window functions
- Power BI dashboard visuals:
  - Warehouse/region throughput
  - Delay/processing-time distributions
  - Regional performance maps
- Written insights summary for operations stakeholders.
