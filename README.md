# ecom-warehouse-dbt

> Modern data stack on e-commerce data: BigQuery + dbt, with tested and documented models and a KPI dashboard.

**Status:** under construction. This repository will be published in stages once each piece is reviewed.

## Planned scope
- Staging, intermediate and mart layers with explicit grain per table
- dbt data tests, generated documentation and lineage
- KPI layer: GMV, AOV, conversion, repeat rate, cohort retention
- A dashboard answering a concrete business question about customer retention

## Data
Public synthetic dataset `bigquery-public-data.thelook_ecommerce`. No private or proprietary data is used in this project.
