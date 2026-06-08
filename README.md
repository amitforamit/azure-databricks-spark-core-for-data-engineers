# Azure Databricks Spark Core for Data Engineers

This repository contains course materials and projects for learning Azure Databricks and Apache Spark for data engineering.

## Contents

- **formula1-project** - Full data pipeline project with bronze, silver, and gold layers
- **formula1-project-incremental-load** - Incremental load patterns with orchestration
- **introduction-to-delta-lake** - Delta Lake fundamentals and time travel
- **introduction-to-notebooks** - Databricks notebook basics and utilities
- **introduction-to-unity-catalog** - Unity Catalog configuration and access
- **formula1-full-load-landing** - Full load data files in CSV and JSON formats
- **formula1-incremental-load-landing** - Incremental load data by month

## Project Structure

```
├── databricks-course-v1/          # Main course materials
├── formula1-full-load-landing/    # Full dataset
├── formula1-incremental-load-landing/  # Monthly incremental data
└── databricks_cluster.json        # Cluster configuration
```

## Getting Started

1. Import the DBC file into your Databricks workspace
2. Configure your cluster using `databricks_cluster.json`
3. Execute notebooks from the course materials

## Technologies

- Apache Spark
- Delta Lake
- Unity Catalog
- Databricks Notebooks
- Python & SQL

## License

Course materials for educational purposes.
